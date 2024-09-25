<script>
    import ThemeSwitcher from '$lib/components/ThemeSwitcher.svelte';
    import Accordion from '$lib/components/Accordion.svelte';
    import Stats from '$lib/components/Stats.svelte';
    import Tabs from '$lib/components/Tabs.svelte';
    import LoadingCard from '$lib/components/LoadingCard.svelte';
    import Input from '$lib/components/Input.svelte';
    import Search from '$lib/components/Search.svelte';
</script>

<ThemeSwitcher />

<h1 class="text-3xl font-extrabold">Sonar App</h1>

<div class="tooltip" data-tip="hello">
  <button class="btn">Hover me</button>
</div>

<LoadingCard />

<Search />

<div class="form-control">
  <label class="label cursor-pointer">
    <span class="label-text">Remember me</span>
    <input type="checkbox" checked="checked" class="checkbox" />
  </label>
</div>

<Stats />

<Tabs />

<span class="loading loading-spinner loading-md"></span>

<Accordion />

<input type="range" min="0" max="100" value="40" class="range" />

<div class="rating">
  <input type="radio" name="rating-2" class="mask mask-star-2 bg-orange-400" />
  <input
    type="radio"
    name="rating-2"
    class="mask mask-star-2 bg-orange-400"
    checked="checked" />
  <input type="radio" name="rating-2" class="mask mask-star-2 bg-orange-400" />
  <input type="radio" name="rating-2" class="mask mask-star-2 bg-orange-400" />
  <input type="radio" name="rating-2" class="mask mask-star-2 bg-orange-400" />
</div>

<select class="select select-bordered w-full max-w-xs">
  <option disabled selected>Who shot first?</option>
  <option>Han Solo</option>
  <option>Greedo</option>
</select>

<Input />