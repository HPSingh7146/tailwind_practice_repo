<script>
	import '../app.css';
</script>

<div class="m-3 h-svh">
	<h1 class="text-3xl font-bold mb-2 text-white">First Tailwind CSS</h1>
	<h2 class="text-2xl font-bold text-white">This is a Subtitle</h2>
	<div class="peragraph grid grid-cols-3 gap-4 h-auto text-white my-3">
		<p class=" bg-red-400 rounded-3xl p-3 h-auto col-span-2 text-justify">
			Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dicta asperiores voluptatibus autem
			qui? Quos consequuntur asperiores obcaecati architecto ratione nam magnam similique tempore
			consectetur harum. Omnis excepturi tempore fugiat ducimus. Lorem ipsum dolor sit amet
			consectetur, adipisicing elit. Accusamus aliquid voluptates, nobis assumenda repellendus culpa
			aliquam alias ipsam quod soluta laboriosam! Officiis sed autem libero, enim iure quod id
			tempora? Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero autem mollitia vitae ut
			quam, eveniet explicabo ipsam magnam? Sunt, distinctio? Saepe, nemo? Dolores harum doloremque
			libero sint beatae nulla culpa? Lorem ipsum dolor sit, amet consectetur adipisicing elit.
			Ipsum incidunt omnis odit numquam hic non, ratione quaerat ex veniam adipisci velit
			repellendus? Deleniti dolore aut neque labore rerum voluptate cum.
		</p>
		<p class=" bg-blue-400 rounded-3xl p-3 text-center">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam fuga odit ullam molestias
			dolorum incidunt velit deserunt tenetur, adipisci beatae dignissimos cum iure corporis numquam
			itaque maiores recusandae harum minima. Lorem ipsum, dolor sit amet consectetur adipisicing
			elit. Distinctio cupiditate, laborum harum saepe odio veniam vitae quae eius facilis aliquam
			nemo cumque repudiandae placeat id sunt ipsa, dolorum hic fugit.
		</p>
		<div class="squers grid grid-cols-3 gap-4">
			<div class="yellow bg-green-600 h-60 rounded-3xl"></div>
			<div class="yellow bg-pink-600 h-60 rounded-3xl"></div>
			<div class="yellow bg-sky-600 h-60 rounded-3xl"></div>
		</div>
		<div class="yellow bg-blue-950 h-60 rounded-3xl col-span-2"></div>
	</div>
	<div class="inputops m-3 bg-cyan-800 p-3 rounded-3xl grid grid-cols-2">
		<input type="text" placeholder="Type here" class=" bg-red-800 p-3 rounded-xl mr-3 text-slate-200 text-lg outline-none border-2" />
		<div class=" bg-yellow-600 p-3 rounded-xl flex justify-center">
			<input type="checkbox" name="" id="a" class=" accent-red-600 w-5 h-5 mr-2 mt-0.5 " />
			<label for="a" class=" text-teal-700 text-xl -mt-0.5">Checkbox</label>
		</div>
	</div>
	<div class="buttons flex justify-around bg-gray-900 p-3 text-white rounded-2xl ">
		<button class=" bg-orange-600 p-2 rounded-lg font-bold">Button 1</button>
		<button class=" bg-amber-800 p-2 rounded-lg disabled:bg-slate-700  font-bold" disabled>button 2</button>
	</div>
</div>

<slot />
