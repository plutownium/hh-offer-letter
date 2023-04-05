<script>
  import BigBeautifulButton from '../components/BigBeautifulButton.svelte'
  import ExtraPaddingLeft from '../components/ExtraPaddingLeft.svelte'
  import GreenBox from '../components/GreenBox.svelte'
  import PaddingBox from '../components/PaddingBox.svelte'
  import RedBox from '../components/RedBox.svelte'
  import StandardBox from '../components/StandardBox.svelte'
  import TechniqueHeadline from '../components/TechniqueHeadline.svelte'
  import WideBox from '../components/WideBox.svelte'

  import '../app.css'
  import FloatyHeader from '../components/FloatyHeader.svelte'
  import LandingCTAButton from '../components/LandingCTAButton.svelte'
  import Logo from '../components/Logo.svelte'
</script>

<!-- todo: verify looks good on mobile & tablet -->
<div class="h-full bg-azure">
  <div class="w-full h-full flex justify-center items-center">
    <div class="w-3/5 h-full">
      <div class="mt-24 mb-12">
        <Logo />
      </div>

      <h1 class="mt-8 mb-4 text-3xl font-bold text-blue">
        The secret high earner playbook only a recruiter can tell you about.
      </h1>

      <h1 class="text-jet text-5xl font-bold">
        How to Add Hundreds of Thousands of Dollars to Your Lifetime Earnings With Only A Few Hours
        of Work A Year
      </h1>

      <!-- <h1 class="mt-8 text-5xl">That you won’t get from anyone else!</h1> -->

      <p class="mt-8 text-2xl">
        This playbook <span class="underline">guarantees</span> you end up in the
        <span class="text-blue font-bold">top 10% of earners</span>
        for your role.
      </p>

      <p class="mt-8 text-2xl">
        Note: <span class="underline text-orange font-bold">Regardless of recent tech layoffs</span
        >, this method will net you a 20 to 40% increase in salary.
      </p>

      <p class="mt-8 text-2xl">Are you ready for a pay increase?</p>

      <div class="mt-8 mb-16 w-full flex justify-center">
        <LandingCTAButton />
      </div>
    </div>
  </div>
</div>

<style>
  /* todo: make font work */
  * {
    font-family: 'Source Sans Pro', sans-serif;
  }
</style>
