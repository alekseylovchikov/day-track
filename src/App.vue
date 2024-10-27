<script setup>
import { CheckCircleIcon } from '@heroicons/vue/24/solid'
import {
  ClockIcon,
  ListBulletIcon,
  ChartBarIcon,
} from '@heroicons/vue/24/outline'
</script>

<template>
  <header
    class="sticky top-0 z-20 flex justify-between items-center border-b bg-white p-3"
  >
    <a href="#" class="flex items-center gap-1 text-3xl font-bold">
      <i class="pi pi-list"></i>
      Day Track
    </a>
    <a href="#" class="font-bold">
      <div v-if="false" class="flex items-center gap-2">
        Day complete
        <CheckCircleIcon class="h-7 text-green-500" />
      </div>
      <div v-else class="flex items-center gap-2">
        <div>Progress: <span class="font-mono">20%</span></div>
        <div class="h-3 w-3 rounded-full bg-orange-500"></div>
      </div>
    </a>
  </header>

  <main class="flex flex-grow flex-col">
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facilis fuga
    impedit in incidunt ipsum nam veritatis? Ad adipisci fuga impedit ipsum,
    nobis nostrum possimus quae vel? Atque autem beatae debitis dicta eaque et,
    ex facilis fugit in ipsa laborum laudantium, minus molestias nesciunt nobis
    pariatur perspiciatis placeat quam quis rerum saepe sunt tempora voluptate?
    Dolores eius, et eum fugiat in inventore iure maiores modi nihil nulla odit
    quaerat sapiente similique tenetur voluptas. Accusantium animi aperiam
    autem, consequatur corporis distinctio, eius eligendi excepturi iure,
    laborum molestias placeat possimus reiciendis saepe soluta velit voluptatem.
    Ab, accusantium aspernatur blanditiis consequuntur cum deserunt distinctio
    dolorum eius eos expedita fuga fugiat harum illum iste iusto maxime minima
    modi nam non numquam omnis perspiciatis placeat provident quae quaerat quas
    qui quibusdam quidem quod quos recusandae, reprehenderit sequi soluta
    tempora tenetur, voluptate voluptatum! Ad commodi doloribus ex hic numquam,
    omnis pariatur quo reprehenderit sint vero? Aliquam consequuntur debitis
    ipsa libero nostrum praesentium quam quia quibusdam quos tempore. Culpa
    cumque dolorem dolorum fugit nobis numquam, reprehenderit tenetur
    voluptates. Culpa dicta eveniet ex iure molestias quis quisquam rem rerum
    tenetur voluptate? Ab ad at, corporis dicta, eos ex impedit in modi nihil
    officia, placeat quo quos ratione reiciendis reprehenderit rerum velit! A
    alias architecto corporis dolor excepturi itaque modi nostrum nulla
    perspiciatis quo. Amet asperiores aut, autem beatae commodi consequuntur
    earum eligendi ex fuga libero maiores minima mollitia numquam odio
    perferendis, porro, provident quas quasi quia quibusdam quisquam
    reprehenderit sapiente similique sit ut. Culpa deleniti ea eveniet obcaecati
    odio sequi unde velit veritatis! Accusamus aliquam consequatur debitis
    deleniti eius facilis fuga inventore ipsam iusto laudantium maiores modi
    natus nemo nobis obcaecati odit perspiciatis quae quo reiciendis rem
    repellat repellendus repudiandae saepe, sapiente similique temporibus totam
    velit veniam vero voluptatum. Aspernatur atque beatae delectus deserunt
    dicta dolor dolorum ducimus explicabo fugit inventore ipsa itaque iusto,
    libero magni minima nam nesciunt pariatur perferendis porro possimus
    praesentium quam quidem repudiandae rerum sed unde ut veritatis vero
    voluptas voluptatum? Adipisci asperiores consequuntur cum error et eveniet
    facere ipsam laboriosam magni modi nisi, numquam odio porro quia sit
    suscipit tempore, totam voluptas. Distinctio esse expedita illum molestiae
    necessitatibus similique totam unde. Accusamus beatae eius est hic id
    laboriosam maxime provident repellendus rerum sequi. Adipisci, assumenda, at
    commodi cupiditate deleniti earum et expedita fuga inventore ipsam maiores
    maxime molestias natus nesciunt obcaecati porro provident quos, reiciendis
    sapiente sed sequi temporibus velit vero vitae voluptatem voluptatibus
    voluptatum! At, beatae distinctio doloribus, fuga harum incidunt ipsam
    itaque magni pariatur perferendis quidem repellat repellendus sapiente
    tempora tenetur veritatis voluptatem. Consequatur eius tempora tempore ut?
    Accusantium ad adipisci alias aperiam aspernatur atque autem blanditiis
    dignissimos doloremque est eum facilis ipsa iste, itaque modi nesciunt, nisi
    quaerat quas quisquam quo quod repellat reprehenderit rerum soluta vel vero
    voluptate voluptatibus. Aspernatur in modi nulla voluptas voluptatibus!
    Accusamus alias consequuntur culpa deserunt earum eius error eum excepturi
    impedit in incidunt, inventore, laudantium minus molestiae nemo nihil odio
    quasi reprehenderit sed sequi suscipit temporibus voluptas! Accusantium
    culpa eos illum iste itaque? Cum, quod?
  </main>

  <nav class="sticky bottom-0 z-10 bg-white">
    <ul class="flex items-center justify-around border-t">
      <li class="flex-1">
        <a
          class="flex flex-col items-center p-2 text-xs capitalize"
          href="#timeline"
        >
          <ClockIcon />
          timeline
        </a>
      </li>
      <li class="flex-1">
        <a
          class="flex flex-col items-center p-2 text-xs capitalize"
          href="#activities"
        >
          <ListBulletIcon />
          activities
        </a>
      </li>
      <li class="flex-1">
        <a
          class="flex flex-col items-center p-2 text-xs capitalize"
          href="#progress"
        >
          <ChartBarIcon />
          progress
        </a>
      </li>
    </ul>
  </nav>
</template>
