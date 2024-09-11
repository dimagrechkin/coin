<script setup lang="ts">
import benduren from '../assets/bro-durov.png'
import placeholder from '../assets/placeholder.jpg'

defineProps<{ msg: string }>()
</script>

<template>
  <div class="flex flex-col items-center w-full min-h-screen bg-gray-100 font-tahoma">
    <header class="w-full bg-[#4a76a8] text-white">
      <div class="container mx-auto flex justify-between items-center p-4">
        <div class="text-2xl font-bold">В контакте</div>
        <nav class="flex space-x-4 text-sm">
          <a href="#" class="hover:underline" rel="ugc"> главная </a>
          <a href="#" class="hover:underline" rel="ugc"> о проекте </a>
          <a href="#" class="hover:underline" rel="ugc"> токеномика </a>
          <a href="#" class="hover:underline" rel="ugc"> выйти </a>
        </nav>
        <div class="relative">
          <div class="flex items-center">тонфан</div>
        </div>
      </div>
    </header>
    <main class="mx-auto flex space-x-4">
      <div className="border border-gray-300  !ml-0 bg-[#dae1e9]  max-w-2xl mx-auto font-serif">
        <h1 className="m-2 pl-1 text-xs font-semibold text-[#4a76a8]">
          Бен Дурев <span class="text-xs font-normal text-[#b1b3b9]">(это Вы)</span>
        </h1>
        <div className="flex  border-gray-300 bg-white pt-4 p-4 border border-gray-300">
          <div className="w-1/3 pr-4">
            <img :src="benduren" alt="Profile" class="w-full object-cover aspect-[2/4] mb-2" />
            <div class="flex flex-col space-y-2 bg-[#EFF0F4] p-2">
              <button class="bg-[#577AA0] text-white text-xs py-2 px-4 hover:bg-[#608EB2]">Отправить сообщение</button>
              <button class="bg-[#577AA0] text-white text-xs py-2 px-4 hover:bg-[#608EB2]">Добавить в друзья</button>
            </div>
            <div class="mt-2">
              <button className="w-full text-[#4a76a8] text-left py-1 px-2 text-sm">Видео Бена</button>
              <button className="w-full text-[#4a76a8] border-b border-gray-300 text-left py-1 px-2 text-sm">
                Подписчики Бена
              </button>
              <button className="w-full text-[#4a76a8] text-left py-1 px-2 text-sm">Отправить подарок</button>
              <h3 className="bg-[#dae1e9] p-1 text-[#4a76a8] text-sm mt-2">
                <div class="flex justify-between">
                  <div class="pl-1 text-xs font-semibold">Друзья</div>
                  <div class="text-[#b1b3b9] hover:underline text-xs">новости</div>
                </div>
              </h3>
              <div className="bg-slate-100 p-1 text-[#b1b3b9] text-sm ">
                <div class="flex justify-between"><div class="font-medium pl-1 text-xs">677 друзей</div></div>
              </div>

              <div class="grid gap-2 sm:grid-cols-2 md:grid-cols-3 mt-2">
                <div>
                  <img
                    class="object-cover object-center w-full h-14 max-w-full"
                    src="https://images.unsplash.com/photo-1499696010180-025ef6e1a8f9?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=1470&amp;q=80"
                    alt="gallery-photo"
                  />
                </div>
                <div>
                  <img
                    class="object-cover object-center w-full h-14 max-w-full"
                    src="https://images.unsplash.com/photo-1432462770865-65b70566d673?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1950&amp;q=80"
                    alt="gallery-photo"
                  />
                </div>
                <div>
                  <img
                    class="object-cover object-center w-full h-14 max-w-full"
                    src="https://images.unsplash.com/photo-1497436072909-60f360e1d4b1?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=2560&amp;q=80"
                    alt="gallery-photo"
                  />
                </div>
                <div>
                  <img
                    class="object-cover object-center w-full h-14 max-w-full"
                    src="https://images.unsplash.com/photo-1493246507139-91e8fad9978e?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=2940&amp;q=80"
                    alt="gallery-photo"
                  />
                </div>
              </div>
            </div>
          </div>
          <div className="w-2/3">
            <div className=" p-4 mb-4">
              <h2 className="font-bold text-[#4a76a8] text-sm">Бен Дурев</h2>
              <div className="text-[#b1b3b9] text-sm  mb-4">Обновлено 7 дней назад</div>
              <table className="w-full text-sm border-t border-gray-300">
                <tbody>
                  <tr>
                    <td className="pr-2 text-[#b1b3b9]">Пол:</td>
                    <td class="text-[#4a76a8] hover:underline">мужской</td>
                  </tr>
                  <tr>
                    <td className="pr-2 text-[#b1b3b9]">Семейное положение:</td>
                    <td class="text-[#4a76a8] hover:underline">не женат</td>
                  </tr>
                  <tr>
                    <td className="pr-2 text-[#b1b3b9]">День рождения:</td>
                    <td class="text-[#4a76a8] hover:underline">10 октября 1984</td>
                  </tr>
                  <tr>
                    <td className="pr-2 text-[#b1b3b9]">Родной город:</td>
                    <td class="text-[#4a76a8] hover:underline">Париж</td>
                  </tr>
                  <tr>
                    <td className="pr-2 text-[#b1b3b9]">Полит. взгляды:</td>
                    <td class="text-[#4a76a8] hover:underline">умеренные</td>
                  </tr>
                  <tr>
                    <td className="pr-2 text-[#b1b3b9]">Религ. взгляды:</td>
                    <td class="text-[#4a76a8] hover:underline">Жизнь</td>
                  </tr>
                  <tr>
                    <td className="pr-2 text-[#b1b3b9]"></td>
                    <td class="text-[#4a76a8]">
                      <button class="hover:underline text-nowrap">Показать полную информацию</button>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
            <div className="p-4">
              <h3 className="bg-[#dae1e9] p-1 text-[#4a76a8] text-sm mb-2">
                <div class="flex justify-between">
                  <div class="font-semibold pl-1 text-xs">124 фотографии</div>
                  <div class="text-[#b1b3b9] semi-bold hover:underline text-xs pr-1">все фото</div>
                </div>
              </h3>

              <div class="grid gap-1 sm:grid-cols-2 md:grid-cols-4 mb-2">
                <div>
                  <img
                    class="object-cover object-center w-full h-20 max-w-full"
                    src="https://images.unsplash.com/photo-1499696010180-025ef6e1a8f9?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=1470&amp;q=80"
                    alt="gallery-photo"
                  />
                </div>
                <div>
                  <img
                    class="object-cover object-center w-full h-20 max-w-full"
                    src="https://images.unsplash.com/photo-1432462770865-65b70566d673?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1950&amp;q=80"
                    alt="gallery-photo"
                  />
                </div>
                <div>
                  <img
                    class="object-cover object-center w-full h-20 max-w-full"
                    src="https://images.unsplash.com/photo-1497436072909-60f360e1d4b1?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=2560&amp;q=80"
                    alt="gallery-photo"
                  />
                </div>
                <div>
                  <img
                    class="object-cover object-center w-full h-20 max-w-full"
                    src="https://images.unsplash.com/photo-1493246507139-91e8fad9978e?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=2940&amp;q=80"
                    alt="gallery-photo"
                  />
                </div>
              </div>
              <h3 className="bg-[#dae1e9] p-1 text-[#4a76a8] text-sm ">
                <div class="flex justify-between">
                  <div class="font-semibold pl-1 text-xs">3234 постов</div>
                  <div class="text-[#b1b3b9] semi-bold hover:underline text-xs pr-1">все посты</div>
                </div>
              </h3>
            </div>

            <div className="max-w-xl p-4">
              <div className="flex flex-row gap-4">
                <div className="h-60 w-60">
                  <img alt="Profile picture" :src="benduren" className="bject-cover" />
                </div>
                <div className="flex flex-col">
                  <h2 className="font-bold text-[#4a76a8] text-sm">Бен Дурев</h2>
                  <p className="text-sm text-muted-foreground pb-2">
                    Today one of my favorite bands — The Prodigy — have launched an official VK page. The world's most
                    famous DJs Tiësto and Armin van Buuren launched theirs a few weeks ago. They post all their songs up
                    with a lot of exclusive photos on VK.
                  </p>

                  <div class="flex flex-row justify-between">
                    <img
                      :src="placeholder"
                      alt="Collage of musicians"
                      className="w-1/3 mr-4 "
                      height="200"
                      width="400"
                    />
                    <div class="flex flex-col gap-4">
                      <p className=" text-[#4a76a8] text-sm font-semibold">Celebrities on VK</p>
                      <p className=" text-muted-foreground text-sm">Artists, Musicians and other stars</p>
                    </div>
                  </div>

                  <div>
                    <div className="flex items-center justify-between">
                      <p className="text-sm text-muted-foreground mt-1">
                        <span class="text-[#b1b3b9]">1 Сен 2024</span> |
                        <span class="text-[#4a76a8] hover:underline">Reply</span>
                      </p>
                      <div className="mr-2 h-4 w-4"></div>
                      <span class="text-xs font-semibold text-[#4a76a8] hover:underline">15905</span>
                      <div className="mr-2 h-4 w-4"></div>
                      <span class="text-xs font-semibold text-[#4a76a8] hover:underline">3957</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- <div className="p-4">
            <h3 className="bg-[#dae1e9] border border-gray-300 p-4 text-[#4a76a8] text-base font-semibold mb-2">Информация</h3>
            <h4 className="text-[#4a76a8] font-semibold mt-2 text-base">Контактная информация</h4>
            <p className="text-sm"><span class="text-[#b1b3b9]">Веб-сайт:</span> <span class="text-[#4a76a8]">http://vkontakte.ru</span></p>
            <h4 className="text-[#4a76a8] font-semibold mt-2 text-base">Личная информация</h4>
            <p className="text-sm"><span className="text-[#b1b3b9]">Деятельность:</span> <span class="text-[#4a76a8]">UNESCO, MENSA High IQ Society, Интернет, PHP, MySQL, CSS, XML, DOM, GNU, Debian, UNIX, Social Networking, новые технологии, Cisco, webdev</span></p>
            <p className="text-sm"><span className="text-[#b1b3b9]">Любимая музыка:</span> <span class="text-[#4a76a8]">The Beatles, RHCP, Louis Armstrong, Frank Sinatra, Blackmore's Night, Rammstein, Vanessa Mae, Snoop Dogg, Звуки природы, Mylène Farmer, Andrew Lloyd Webber, T.A.T.U., The Killers</span></p>
            <p className="text-sm"><span className="text-[#b1b3b9]">Любимые фильмы:</span> <span class="text-[#4a76a8]">Matrix, Fight Club, V for Vendetta, Lord of the Rings, Lord of War, The Hitchhiker's Guide to the Galaxy, Godfather</span></p>
            <p className="text-sm"><span className="text-[#b1b3b9]">Любимые игры:</span><span class="text-[#4a76a8]"> Dreamfall, The Longest Journey, Discworld 2, Discworld Noir, Quake 3, Starcraft, Fallout</span></p>
            <p className="text-sm"><span className="text-[#b1b3b9]">Любимые цитаты:</span><span class="text-[#4a76a8]"> Не беспокойся о том, что у тебя нет высокого чина. Беспокойся о том, достоин ли ты того, чтобы иметь высокий чин.</span></p>
            <p className="text-sm"><span className="text-[#b1b3b9]">О себе:</span> Больше всего ценю в людях честность, трудолюбие и преданность идее.</p>
          </div> -->
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<style scoped></style>
