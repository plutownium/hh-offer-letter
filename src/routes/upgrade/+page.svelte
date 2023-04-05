<script>
  import { onMount } from 'svelte'

  import BigBeautifulButton from '../../components/BigBeautifulButton.svelte'
  import ExtraPaddingLeft from '../../components/ExtraPaddingLeft.svelte'
  import PaddingBox from '../../components/PaddingBox.svelte'
  import StandardBox from '../../components/StandardBox.svelte'
  import WideBox from '../../components/WideBox.svelte'

  import '../../app.css'
  import FloatyHeader from '../../components/FloatyHeader.svelte'

  onMount(() => {
    document.body.style.visibility = 'visible'
  })
</script>

<!-- fixme: FOUC -->
<FloatyHeader />
<div class="h-24" />
<div class="w-full flex flex-col items-center bg-blue">
  <div class="w-11/12 sm:w-10/12 md:w-9/12 mt-8 h-full">
    <div class="pb-12 h-3/5 flex flex-col items-center">
      <h1 class="mt-8 font-bold text-center text-oxford text-3xl sm:text-5xl">
        Uncover The Proven Method You Won’t Find On Google
      </h1>

      <h1 class="mt-8 font-bold text-center text-oxford text-3xl sm:text-5xl">
        Increase Your Pay As Much As Fifty Percent, Trigger Bidding Wars, and Join the Top Ten
        Percent of Earners…
      </h1>

      <h1 class="mt-6 font-bold text-center text-oxford text-3xl sm:text-5xl">
        Even If You Currently Struggle to Get Interviews!
      </h1>
    </div>
    <div class="h-2/5 pb-4">
      <div
        class="h-full px-4 sm:px-12 lg:px-24 xl:px-40 py-8 flex justify-center flex-col items-center bg-sand"
      >
        <h2 class="font-bold text-center text-oxford text-xl">
          This is a 1718x ROI for anyone working in the following roles.
        </h2>
        <p class="font-bold text-lg">(We did the math.)</p>
      </div>
    </div>
  </div>
</div>
<div class="pb-8 w-full flex flex-col items-center">
  <div class="w-11/12 sm:w-10/12 md:w-9/12 px-8">
    <!-- // placeholder -->
    <h2 class="mt-8 mb-2 text-3xl sm:text-4xl">Are you a…</h2>
    <ExtraPaddingLeft>
      <ul class="list-with-bullets">
        <li>Software developer</li>
        <li>Cybersecurity engineer</li>
        <li>Systems engineer</li>
        <li>Cloud engineer</li>
        <li>Program manager</li>
        <li>Project manager</li>
        <li>Person in the above list who wants to see a $20,000 to $60,000 pay increase.</li>
        <li>Person in the above list who wants to be in the top 5% of earners for their role.</li>
      </ul>
    </ExtraPaddingLeft>

    <p>If you are, ask yourself:</p>

    <p class="font-bold">
      Have you found yourself thinking or saying something that would fit in with the quotes below?
    </p>

    <p>
      “People say my role is high paying, but I don’t feel that way about it at all. I know I’m
      underpaid.”
    </p>

    <p>“Even if I’m not exactly bottom 10% of earners, I still feel like I am.”</p>

    <p>
      “I send out hundreds of applications and receive a completely underwhelming response, even
      though I supposedly have an ‘in demand’ skill.”
    </p>

    <p>“I’d rather be top 10% or even top 30% of income for my role.”</p>

    <p>“I don’t care if the market is good or bad, I want to be in demand.”</p>
  </div>
</div>

<div class="">
  <StandardBox>
    <PaddingBox
      ><div class="">
        <h2 class="text-oxford text-4xl">
          <span class="font-bold">If this is you,</span> it means you’re about to find out how you could
          increase your total compensation by 20 to 40% using a few hours of work.
        </h2>
      </div>
      <div>
        <p>
          It means you get the opportunity to increase your compensation by tens of thousands of
          dollars.
        </p>

        <p>You’ll be able to do this not just once, but over and over throughout your career.</p>

        <p>You’ll leave your peers and colleagues in the industry in the dust monetarily.</p>

        <p>How?</p>

        <p>
          By following <span class="underline"
            >a set of proven methods and techniques that hundreds of recruiters could tell you about</span
          >…
        </p>

        <p>But none will.</p>

        <p>
          Because improving your job hunting and negotiation abilities would be bad for their
          clients, they don’t want you to improve.
        </p>

        <p class="underline">
          In fact, recruiters and employers celebrate giving employees the short end of the stick in
          salary negotiations.
        </p>

        <p>However, I’m here to help.</p>

        <p>To tell you: It doesn’t have to be this way.</p>

        <p>
          You don’t have to continue as an underpaid, undervalued member of your team for the rest
          of your career.
        </p>

        <p>
          You don’t have to disappoint yourself, year after year, by failing to secure a raise from
          your employer.
        </p>

        <p>Or by avoiding the discussion entirely.</p>

        <p>
          The difficulty in securing a raise is not your doing. Society rigs the game against you,
          and the only place you have to turn to for advice is the Internet.
        </p>

        <p>Yet the Internet isn’t always helpful!</p>
      </div>
      <div class="">
        <h2 class="text-jet text-3xl">
          Millions of people are underpaid. You shouldn’t feel bad about it, but you should try to
          fix it.
        </h2>
      </div>
      <div>
        <p>
          If the Internet's advice on this topic is so common, why does the question come up over
          and over on Reddit?
        </p>

        <p>
          Shouldn’t Redditors be able to solve this so well that the search function is all anyone
          needs?
        </p>

        <p>Here’s typical Redditor advice you’ll receive about what to do when you’re underpaid:</p>

        <div class="mt-4">
          <img
            src="/images/img00a.png"
            alt="A reddit post that reads: Interview with other companies to find out what your labor is actually worth"
          />
        </div>
        <p>The advice shows up again in this thread:</p>

        <div class="mt-4">
          <img src="/images/img01.png" alt="Am I being underpaid at my current job?" />
        </div>

        <div class="mt-4">
          <img
            src="/images/img02.png"
            alt="A reddit post that reads: Best way to find out is to apply to new roles & see what you get offered"
          />
        </div>

        <p>
          The reason this advice shows up so often is that it works. But even when people apply,
          they often come up short. Job hunting and interview skills often need work.
        </p>

        <p>
          You can’t find better job offers if you can’t get to the interview stage… or make
          interviewers love you as a candidate.
        </p>

        <p>Here’s another redditor echoing this same truth:</p>

        <div class="mt-4">
          <img
            src="/images/img03.png"
            alt="A reddit post that reads: You are only worth what someone is willing to pay you"
          />
        </div>

        <p>Yet none of these posts address the glaring, valley-wide room for improvement:</p>

        <p>Your job hunting and interview skills.</p>

        <p>If they’re weak, you’ll end up with the same low pay as you had before.</p>

        <p>And nothing will change.</p>
      </div>
    </PaddingBox>
  </StandardBox>
</div>

<!-- // todo: style bg color with gentle shade to alert reader -->
<WideBox>
  <div class="mt-8 px-4 sm:px-12 lg:px-24 xl:px-40 py-2 bg-celeste">
    <div>
      <h2 class="text-3xl text-center">
        “I have one of the highest demand skills in tech… yet I feel like I’m making minimum wage
        all over again."
      </h2>
    </div>
    <div class="mb-8">
      <p>Ouch.</p>

      <p>You thought your financial woes were over when you went into tech.</p>

      <p>Society told you it’s an “in demand role,” yet you know you’re being underpaid.</p>

      <p>Sites that report compensation say your compensation should be higher.</p>

      <p>Friends from other companies say your compensation should be higher.</p>

      <p>Your boss says your compensation… is right where it belongs!</p>

      <p>
        That it is “all they can afford at the moment” even though your coworker just got a raise.
      </p>

      <p>
        You’d leave for another company if you could. Yet when you try to find a higher paying role,
        it’s tough to find one!
      </p>

      <p>Aren’t your skills supposed to be in demand?</p>

      <p>What’s going on here?</p>
    </div>
  </div>
</WideBox>

<StandardBox>
  <PaddingBox>
    <div>
      <div>
        <!-- // todo: color this entire box a color bg color so get attention -->
        <h2 class="text-3xl">
          If you’d like to make the change described below, keep reading to find out how.
        </h2>
      </div>
      <h3 class="text-2xl">Before state:</h3>
      <p>
        You feel undervalued and know it’s true. You find yourself pinching pennies when you never
        thought you’d have to. Friends and people on forums say your pay should be higher. You want
        to be the type of person who can brag and help others get ahead. But you don’t know how to
        make a change.
      </p>
      <p>
        Worse, you worry that the difficulties finding a job aren’t just about the resumes you’re
        sending out, but about you personally. You worry that you’re going to be undervalued at your
        role forever. Decades of it.
      </p>
    </div>

    <div>
      <h3 class="text-4xl">I’d like to show you how you can get from there, to here:</h3>
    </div>

    <div>
      <h3 class="text-2xl">After state:</h3>

      <p>
        You’re paid what you’re worth. Ahead of the pack. The companies you work for see you as top
        talent, and pay accordingly.
      </p>

      <p>Your friends at other companies wish they knew your secret.</p>

      <p>
        You post a yearly “here’s my TC” and find yourself leading the pack on Team Blind. You offer
        advice to people who are in your past position. (And it’s a referral to my program.)
      </p>

      <p>
        You no longer worry; you know you’re a strong candidate who will have success after success
        finding new roles with higher pay.
      </p>
    </div>
  </PaddingBox>
</StandardBox>
<WideBox>
  <!-- px-4 sm:px-12 lg:px-24 xl:px-40 -->
  <div class="px-2 sm:px-6 lg:px-12 xl:px-20">
    <h3 class="px-2 sm:px-6 lg:px-12 xl:px-20 text-2xl">Would you rather have:</h3>
    <!-- // todo: "this' on " the left, "or this" on the right. -->
    <!-- todo: style on mobile -->
    <div class="flex flex-col sm:flex-row">
      <div
        class="py-4 pl-2 sm:pl-6 lg:pl-12 xl:pl-20 pr-1 sm:pr-2 lg:pr-6 xl:pr-12 text-strong-coral"
      >
        <h4 class="mb-4 underline text-2xl font-bold">This...</h4>
        <ul class="list-with-bullets-with-big-text pl-5 text-3xl">
          <li>
            Turned down for a raise by your boss. He raises his hand to silence you mid pitch.
          </li>
          <li>See your biweekly payday hit your bank account and wish for more.</li>
          <li>Know yourself as a financial underperformer</li>
          <li>
            Rejection letters pile up in your inbox every time you apply… but you get few
            interviews.
          </li>
        </ul>
      </div>
      <div
        class="py-4 pr-2 sm:pr-6 lg:pr-12 xl:pr-20 pl-1 sm:pl-2 lg:pl-6 xl:pl-12 text-strong-emerald"
      >
        <h4 class="mb-4 underline text-2xl font-bold">Or this?</h4>

        <ul class="list-with-bullets-with-big-text pl-5 text-3xl">
          <li>
            Welcomed into day 1 of a new role with 37% higher TC; they say “glad we got you out of
            there”
          </li>
          <li>
            See your biweekly pay hit and feeling relieved, every time it happens, for weeks or
            months
          </li>
          <li>Know your value and see it reflected in your bank statements.</li>
          <li>A calendar full of job interviews for higher income roles.</li>
        </ul>
      </div>
    </div>
    <div class="px-2 sm:px-6 lg:px-12 xl:px-20">
      <p>If you find yourself living through the left column, you should know:</p>

      <p>Your <span class="italic">job skills</span> don’t tell the whole story.</p>

      <p class="underline">
        Your <span class="font-bold">job hunting skills</span> contribute just as much if not more to
        your compensation.
      </p>
    </div>
  </div>
</WideBox>

<StandardBox>
  <PaddingBox>
    <div>
      <h3 class="text-2xl">With the advice you receive today, you’ll have:</h3>
      <ul class="list-with-bullets pl-5">
        <li>A calendar that has an interview on 9 of 10 work days.</li>
        <li>Some days have more than one interview!</li>
        <li>
          Receive 4 interview requests in the same day… even though you only sent 100 applications.
        </li>
        <li>
          House hunting trips into neighborhoods that were out of your price range a year ago.
        </li>
      </ul>

      <h3 class="text-2xl">And you’ll avoid:</h3>

      <ul class="list-with-bullets pl-5">
        <li>
          Sending your resume out 2,000x only to get an offer that is “pretty much the same” as what
          you have now.
        </li>
        <li>
          Seeing people on /r/ITCareerQuestions talk about their raises… while your TC stays the
          same.
        </li>
        <li>Being a productive member of the team year after year without recognition.</li>
        <li>Working with the nagging feeling that you’re less than you’re worth.</li>
        <li>Being “stuck” even though you got “one of the good jobs.”</li>
        <li>Feeling disappointed in yourself.</li>
        <li>Being politely declined a raise.</li>
      </ul>
    </div>
    <div>
      <p>
        If you are a great software developer, but you aren’t adept at selling yourself and your
        skills…
      </p>

      <p>You’ll be continually underpaid, no matter how good you are at your actual job.</p>

      <p>
        The facts are that <span class="underline">presentation and people skills matter</span>.
      </p>

      <p class="underline">Outreach and sales skills matter.</p>

      <p>
        Lots of software engineers, cybersecurity experts, etc. who are great at their technical
        skills underperform in interviews.
      </p>

      <p>
        And lots of managers who are great with people <span class="italic">still</span> underperform
        in interviews!
      </p>

      <p>The good news is, this is mostly fixable with even a few weeks of work.</p>
    </div>
  </PaddingBox>
</StandardBox>
<StandardBox
  ><PaddingBox>
    <div>
      <!-- // big white colored text against white bg  -->
      <h2 class="text-green text-4xl">
        To the degree that you’re willing to practice a handful of <span
          class="font-bold text-strong-emerald">well defined, doable exercises,</span
        > you will be able to learn to interview like an expert negotiator.
      </h2>
    </div>
    <div>
      <p>Consider this image:</p>

      <div class="mt-4">
        <img
          class="h-96 max-w-full"
          src="/images/img05.png"
          alt="Ryan Gosling and Steve Carrell. Gosling is dressed fashionably; Carrell is dressed like a slob."
        />
      </div>

      <p>
        Steve Carrell is dressed in a poorly fitted polo, baggy jeans and beat up running shoes.
        Ryan Gosling’s character, in contrast, has a sharp fitted shirt, slacks and aesthetic
        footwear. He also stands up straighter.
      </p>

      <p>We recognize that these are surface level traits, yet they are all we see.</p>

      <p>Interviews are the same way.</p>

      <p class="font-bold">
        Luckily, we can quickly and easily improve our performance in the job search by changing how
        we present ourselves.
      </p>

      <p>
        Though our actual skills and productivity remain the same, by changing others’ perceptions
        of them.
      </p>

      <p class="font-bold">
        Our goal is for you to be the chad engineer, while the hiring manager is Steve Carrell’s
        character.
      </p>

      <div class="mt-4">
        <img
          class="h-96 max-w-full"
          src="/images/img06.png"
          alt="Same as before, but now Carrell is labeled 'manager' and Gosling is 'you'."
        />
      </div>

      <p>You want the hiring manager to be wowed by your presentation.</p>

      <p>That’s the money ticket.</p>

      <p>Yet no one talks about the “how” of being a “wow” type of candidate.</p>

      <p>Because they don’t know what to do, or how to define it.</p>

      <p>Here’s more “advice” on the topic of being underpaid:</p>

      <!-- todo: img 1, img 2 -->

      <div class="mt-4">
        <img
          class=""
          src="/images/img07.png"
          alt="A reddit post that reads: I know I'm underpaid for my level. What's the best way to bring this up?"
        />
      </div>

      <div class="mt-4">
        <img
          class=""
          src="/images/img08.png"
          alt="A reddit post that reads: 'You don't, you leave for another company'."
        />
      </div>

      <h3 class="text-2xl">
        But we’re back to the same issue! If your skills are sharp, yet your offers don’t reflect
        what you feel you’re worth…
      </h3>

      <p>What are you to do?</p>

      <p>
        The way it is now, <span class="underline"
          >there’s no one on your team on this issue except you and me</span
        >.
      </p>

      <h2 class="text-3xl">I’ll tell you how it really is:</h2>

      <p>
        You’re underpaid because <span class="text-orange font-bold">the entire system</span> is setup
        to hold you back from being well paid to the best of its ability.
      </p>

      <p>Your boss wants your pay to be low.</p>

      <p>Recruiters want your pay to be low.</p>

      <p>Other companies want your pay to be low.</p>

      <p>All of them have one thing in common:</p>

      <p>They’re out to help themselves, not you.</p>

      <p>So how can you get ahead when everyone is trying to hold you back?</p>

      <h2 class="text-center text-blue font-bold text-4xl">
        You need to have an in-the-know IT recruiter who’s <span class="underline"
          >on your side</span
        >.
      </h2>

      <p>
        You’ll learn a lot of hidden gems of wisdom that only experienced recruiters could tell you.
      </p>

      <p>Lots of them could tell you these secrets but won’t.</p>

      <p>I’m the exception.</p>

      <p>My 9-5 involves watching 30 companies make hiring decisions every single week.</p>

      <p>I see who they hire… and who they don’t.</p>

      <p>I see the patterns.</p>

      <p>The stories.</p>

      <p>The case by case example of what an in-demand candidate does and doesn’t do.</p>

      <p>Yet I’m willing to help you.</p>

      <p class="font-bold">
        Because helping someone change careers and go from $40,000/year to $100,000/year is
        satisfying.
      </p>

      <p class="font-bold">
        Because helping someone go from $90,000/year to $130,000/year means I sleep great that
        night.
      </p>

      <p>Last year I helped someone go from $20k to $90k. Felt great.</p>

      <p>
        In fact, I have so much to tell you that I can give away lots of advice <span
          class="underline">for free</span
        > and still have more to tell you after you invest.
      </p>
    </div>
  </PaddingBox></StandardBox
>

<StandardBox
  ><PaddingBox>
    <div>
      <h2 class="text-4xl">Four Free Ways to Improve Your Resume Today</h2>
    </div>
    <div>
      <p class="">If the free advice is good, what's the full service like?</p>
      <h3 class="mt-8 text-2xl">
        <span class="underline">Tip #1</span>: Use a two or three page resume.
      </h3>

      <div class="mt-4">
        <img
          class=""
          src="/images/img09.png"
          alt="A Headhunter tweet that says: 'Of the 50 candidates I've placed in the last year, exactly one had a single page resume.'"
        />
      </div>
      <p>The “It has to fit on one page” advice is bullshit.</p>
      <p class="font-bold">
        Of the fifty candidates I helped get hired this year, 49 of them used a two or three page
        resume.
      </p>
      <p>
        The truth is that <span class="underline"
          >if you use a one page resume, employers will presume that’s all you had to offer</span
        >.
      </p>
      <p>Are you using a one page resume right now?</p>
      <p>
        So long as you follow the next tips, you’ll see an improvement by adding a second page.
        (Supposing you don’t adhere to them already, anyway.)
      </p>
      <h3 class="text-2xl">
        <span class="underline">Tip #2</span>: Use a simple low-design approach.
      </h3>

      <p>
        While you don’t want to present a document with zero formatting, making the resume flashy is
        also the wrong approach.
      </p>
      <p>Recruiters will throw out a resume that looks flashy before they even read it.</p>
      <p>You want your features and benefits to stand on their own.</p>
      <p>The design takes attention away from the bullet points.</p>
      <p>So by using low-design, you allow the bullet points to “speak for themselves.”</p>
      <h3 class="text-2xl">
        <span class="underline">Tip #3</span>: Use language from the job post you are applying to.
      </h3>

      <p>It takes far more time, but the upside is huge: Recruiters will recognize</p>
      <p>Your application really was crafted specifically for that posting.</p>
      <p>Your skills really match exactly what they asked for.</p>
      <p>Without your application matching the job post’s language…</p>
      <p>The recruitment team has to do a lot of thinking to understand how you’d fill the role.</p>
      <p>When you use language that matches the job post, they understand exactly:</p>
      <p>“Oh yeah, s/he would be able to fulfill requirements X, Y and Z.”</p>
      <p>That means you’ll get more interviews.</p>
      <p>That means you’ll be in demand.</p>
      <p>That means you’ll be offered more money.</p>
      <h3 class="text-2xl">
        <span class="underline">Tip #4</span>: Using specific detailed bullet points that are
        quantified.
      </h3>

      <p>If you aren’t in the habit of doing this, it will take work to start doing it.</p>
      <p>But…</p>
      <p>It will be well worth the effort.</p>
      <p><span class="underline">Don’t say</span>: “Reduced call time from the database.”</p>
      <p>
        <span class="underline">Do say</span>: “Reduced call time from the database by 37% by
        decreasing read algorithms from O(nlogn) to O(n).”
      </p>
      <p>
        <span class="underline">Don’t say</span>: “Decreased page load speed by converting to
        Tailwind, yielding a decrease in the bounce rate.”
      </p>
      <p>
        <span class="underline">Do say</span>: “Decreased page load speed by 48% by converting from
        CSS to Tailwind, yielding a 26% decrease in the bounce rate.”
      </p>

      <p>
        Similar to Tip #2, the issue is that the vague option leaves recruiters to fill in the
        blanks themselves.
      </p>
      <p>(And they don’t fill them in. Because it would take effort and require presumptions.)</p>
      <p>
        By telling them specifically, quantifiably, what you changed during your previous roles, you
        go from…
      </p>
      <p>“Meh, not sure what this means.”</p>
      <p>To…</p>
      <p>“Wow, that would be such an improvement here.”</p>
      <p class="font-bold">These tips work and work well.</p>
      <p class="font-bold">Applying them will get you a better response rate immediately.</p>
      <p class="font-bold">
        But you’ll get far further by investing in getting the full Headhunter treatment.
      </p>

      <p>If these tips are “all you need,” I wish you the best…</p>
    </div>
  </PaddingBox></StandardBox
>

<StandardBox
  ><PaddingBox>
    <div>
      <h2 class="text-3xl">
        If you’re not the type of person to ask for help from an expert, the above advice will be
        all you need to make sure you’re “dialing in the basics.”
      </h2>

      <h2 class="text-3xl">
        But if you sense that <span class="underline"
          >investing in your career’s success is the right move</span
        >, and you’d like to receive <span class="underline">recruiter secrets</span>…
      </h2>

      <h2 class="text-3xl">
        Read on to find out everything you’d need to know to make an informed decision.
      </h2>
    </div>
    <div>
      <p>First, let’s address who this is not for:</p>

      <li class="mt-4">
        You’re convinced your resume and job hunting skills have to be “perfect” to land a pay
        increase.
      </li>

      <p>
        You don’t have to be perfect but you do have to follow the advice you receive. If you’re
        convinced you’ll need to be perfect and therefore this won’t help, this isn’t a good fit for
        you.
      </p>

      <li class="mt-4">You’re certain you’re already paid what you’re worth.</li>

      <p>Almost all employees have room for improvement in their compensation.</p>

      <p>If you’re a top 3% earner at your company and you know it, you don’t need this advice!</p>

      <li class="mt-4">You think presenting yourself well to gain money would be “unethical.”</li>

      <p>Or…</p>

      <li class="mt-4">
        You can’t or won’t take advice about how to present yourself in interviews.
      </li>

      <p>Were I to advise you on how to do your job, you would be right to ignore me.</p>

      <p>But if I advise you on how to acquire your job, my advice is the best of the best.</p>

      <p>
        So if your ego is too big to acknowledge that I know better than you on this topic, this
        won’t work for you.
      </p>

      <li class="mt-4">
        You think you know better than a recruiter about what does and doesn’t work.
      </li>

      <p>Same story as above. You have to be prepared to execute on the advice you receive.</p>

      <p>If you don’t, my advice won’t work.</p>

      <li class="mt-4">
        You aren’t prepared to use inside secrets to get an edge over competitors.
      </li>

      <p>
        If you’re worried that receiving inside secrets to gain an unfair advantage over employers
        and your competition:
      </p>

      <p>Trust me, your worries are well founded.</p>

      <p>If using insider secrets to get ahead doesn’t appeal to you… you should look elsewhere.</p>
    </div>
  </PaddingBox></StandardBox
>

<StandardBox
  ><PaddingBox>
    <div class="text-center">
      <h3 class="italic text-3xl">Still here?</h3>

      <h3 class="italic text-3xl">Great. Let’s move forward.</h3>
    </div>
    <div>
      <p>We need to talk about what happens when you use a “Do It Yourself” solution.</p>

      <p>I can’t let you go off on your own and get it wrong.</p>

      <p>The stakes are dire:</p>

      <p>Do you want to change and start getting right in your career?</p>

      <p>Do you want to make the most of the valuable skills you worked hard to acquire?</p>

      <p>
        If so, I recommend avoiding the “free” advice on the web (that costs you time and
        disappointment trying it out)
      </p>
    </div>
    <div>
      <h2 class="text-3xl">
        Why <span class="font-bold">Google Doesn’t Work</span>, Gives You Bad Advice, and Leaves You
        Struggling to Make Sense of Advice All On Your Own
      </h2>

      <p class="mb-4">Here’s what you can find out for free on Google:</p>
      <ul class="list-with-bullets pl-5">
        <li>“Use a one page resume.” (A myth.)</li>
        <li>Repetitious advice you’re already be taking.</li>
        <li>Generic advice that applies to a similar role but not yours.</li>
        <li>Advice about what worked… for a graduate from an Ivy League university.</li>
        <li>Long blog posts that are 99% filler and 1% actionable advice.</li>
      </ul>

      <p class="mt-8 mb-4">Yet Google won’t tell you:</p>
      <ul class="list-with-bullets pl-5">
        <li>That some of the highest paid candidates use a 3 page resume.</li>
        <li>The recruiters’ best plays to secure high income in interviews.</li>
        <li>How, specifically, to customize and present your work experience to a job posting.</li>
        <li>
          What even someone without a college degree can do to present themselves in the best light.
        </li>
        <li>
          Dense, action packed advice where applying every word adds $20,000 to $80,000 to your
          salary.
        </li>
      </ul>

      <p class="underline">By the way:</p>

      <p>
        If you really wanted to, yes, you could build a patchwork version of the advice you’d get
        from me using Google.
      </p>

      <p>But it would take months.</p>

      <p>You’d have to slog through repetitious advice.</p>

      <p>Through storms of <span class="italic">bad advice</span>.</p>

      <p>You’d have to have great judgment about what works and doesn’t work.</p>

      <p>You’d have to test it.</p>

      <p>
        And you’d <span class="italic">struggle</span> to test it, because you can only attend so many
        interviews yourself.
      </p>

      <p class="font-bold">
        In contrast, I sit through twenty interviews a week, and have for years.
      </p>

      <p class="font-bold">
        The advice you receive in the guide is based on insights I uncovered while watching hundreds
        of interviews take place.
      </p>

      <p>Using Google, you’ll be missing:</p>
      <ul class="list-with-bullets pl-5">
        <li class="mt-4">Step by step instructions to diagnose problems if and when they occur.</li>
        <li>Word by word instructions on how top paid performers present themselves.</li>
        <li>
          The resume writing tips I present to superstar candidates I really want credit for hiring.
        </li>
        <li>Insider secrets about what the current market of companies is really after.</li>
      </ul>

      <p>And using my advice, you’ll advance your career without:</p>

      <ul class="list-with-bullets pl-5">
        <li class="mt-4">
          Receiving a confusing system of twists and turns so daunting you can’t even start to use
          it.
        </li>
        <li>Being told to “start a side hustle” that might take years to start paying off.</li>
        <li>Doing anything unethical or risky for your reputation.</li>
      </ul>

      <p>
        You’ll get advice and instruction that you can start to apply <span class="underline"
          >the same day you get it</span
        >.
      </p>

      <p>
        You can use the advice to get an upper hand in negotiations with people who <span
          class="underline">do not care</span
        > about you or your needs.
      </p>
    </div>
  </PaddingBox></StandardBox
>

<StandardBox
  ><PaddingBox>
    <div>
      <h2 class="text-3xl">
        Your employer and the recruiters they work with want you stuck in your low paying position
        for the rest of your life.
      </h2>

      <h2 class="text-3xl">
        They don’t care that you have or will have a family to feed, a house to pay for, and dreams
        all of your own.
      </h2>

      <p>
        My firm’s current roster of clients, and every employer like them including yours, want you
        stuck being undervalued and underpaid for your whole career.
      </p>

      <p>The Applicant Tracking System companies want to stop you from even being considered.</p>

      <p>
        Facts: I have to keep my identity secret to avoid losing my “insider access” to the system.
      </p>

      <p>If my employer or clients found out I was helping you get ahead, they’d fire me.</p>

      <p>Odds are, it’ll happen eventually.</p>

      <p>
        Someone on Twitter will discover my identity, make a call to my boss, and I’ll have to shut
        this down.
      </p>

      <p>
        Or a client will catch me using Twitter (that I sometimes use on my phone at work), do some
        digging, and discover who and how many people I am helping.
      </p>

      <p>And report me.</p>

      <p>And it’ll be over.</p>

      <p>
        It’s only a matter of months until this offer disappears, for reasons stated directly above.
      </p>

      <p>
        The system wants you held down financially, so greedy employers and shareholders don’t have
        to pay you what you’re worth.
      </p>

      <p>So some day I’ll have to stop sharing my secrets with you.</p>

      <p>You’d be better off taking advantage of this opportunity while it lasts…</p>

      <p>But it’s up to you whether you want them.</p>
    </div>
  </PaddingBox></StandardBox
>

<div class="bg-nigh-black">
  <StandardBox
    ><PaddingBox>
      <div class="secret-text-sizing">
        <h2 id="secret-box-headline" class="font-bold text-5xl text-center text-blue">
          The Salary Increase Special
        </h2>
        <h3 id="secret-box-headline" class="text-4xl">
          The secret methods you’ll receive to increase your salary include:
        </h3>

        <p class="">
          <span class="underline font-bold">Secret #1</span>: The three step process to turning your
          work experience into a resume bullet point that looks like a gold mine to hungry
          employers.
        </p>
        <p>
          <span class="underline font-bold">Secret #2</span>: Whether to spam apply or craft a
          custom resume per job ad.
        </p>
        <p>
          <span class="underline font-bold">Secret #3</span>: How you can use LinkedIn to put
          yourself at the front of the line.
        </p>
        <p>
          <span class="underline font-bold">Secret #4</span>: The five most common questions
          employers have about candidates.
        </p>
        <p>
          <span class="underline font-bold">Secret #5</span>: Four objections I hear from employers
          every single week… and how to answer them.
        </p>
        <p>
          <span class="underline font-bold">Secret #6</span>: Who is on your side in the hiring
          process & what to ask them to reveal insights into decision makers’ thought processes.
        </p>
        <p>
          <span class="underline font-bold">Secret #7</span>: Why you should act like you’re all on
          the same team & how that helps you.
        </p>
        <p>
          <span class="underline font-bold">Secret #8</span>: Why keeping your home address on your
          resume could be costing you thousands of dollars a year.
        </p>
      </div>
    </PaddingBox></StandardBox
  >
</div>

<!-- <StandardBox -->
<!-- ><PaddingBox> -->
<div class="mt-20 bg-celeste">
  <WideBox>
    <div class="pb-12 px-4 sm:px-12 lg:px-24 xl:px-40">
      <h2 id="faq-headline" class=" underline text-4xl text-center font-bold text-blue">
        Frequently Asked Questions
      </h2>

      <p class="question-text text-blue">
        Q: Will your service work for me even if I’m not a top performer?
      </p>

      <p>
        I speak to, on average, 12 companies *per week* and have an inside look at what they REALLY
        care about. I’ll tell you exactly what the candidates who get the most offers have in common
        on their resumes.
      </p>

      <p>
        Rate yourself out of 10 at whatever you do. Whatever your rating really is, I’ll add four
        points to how you are perceived via my resume advice.
      </p>

      <p class="question-text text-blue">Q: Will I be able to implement the advice properly?</p>
      <p>
        All day long at my day job, I coach candidates that I think are winners into presenting
        themselves well to employers. I guarantee I can help you make a big improvement to your job
        searching skills that will add 10 to 50% to your compensation.
      </p>
      <p>
        If it doesn’t work for you, you can take the full amount off the cost of my Done For You
        service.
      </p>
      <p class="question-text text-blue">Q: Will this work even if I can’t negotiate?</p>
      <p>This guide will show you proven, tested strategies for negotiating.</p>
      <p class="">
        You’ll receive the <span class="underline">exact strategies and techniques</span> for negotiating
        a higher salary companies can’t counter.
      </p>
      <p class="question-text text-blue">
        Q: Will the guide won’t work even when the economy is bad?
      </p>
      <p>
        When the job market takes a dive, top earners continue to receive the highest compensation
        in the marketplace. <span class="underline"
          >Being good at job hunting, selling yourself and negotiating means that you’ll be paid
          well regardless of how the market is doing</span
        >.
      </p>

      <p class="question-text text-blue">
        Q: What if I’m not good enough at my job to earn more money? What if I haven’t worked hard
        enough to earn a raise?
      </p>
      <p>I’ll tell you directly that this belief is a huge part of why you’re underpaid.</p>
      <p>
        High paid employees recognize that <span class="underline"
          >while hard work does pay off, it isn’t the only variable that decides compensation</span
        >.
      </p>
      <p>The other variables include:</p>
      <ul>
        <li>How well their boss and coworkers like them.</li>
        <li>Whether they present well in interviews.</li>
        <li>How directly the work they produce makes the company money.</li>
        <li>Whether decision makers perceive their contributions as valuable or not.</li>
      </ul>

      <p>
        <span class="italic">So even if you’re a slacker</span>, you can still use this advice to
        earn more money.
      </p>
      <p class="question-text text-blue">Q: What if the company can’t afford to give me a raise?</p>
      <p>
        Your company spends millions of dollars a year on labor. You can estimate this value by
        taking the number of people in your office and multiplying it by your current salary.
        Whether you have 5 coworkers or 50, it’s going to be a number so large that an additional
        $20,000 won’t be noticed.
      </p>
      <p class="question-text text-blue">Q: Could I get this advice from another recruiter?</p>
      <p>
        Nope. Recruiters serve their clients, namely the company will help rip you off. Recruiters
        won’t and don’t tell you the secrets you can only get here.
      </p>
    </div>
  </WideBox>
</div>
<!-- </PaddingBox></StandardBox -->
<!-- > -->

<StandardBox>
  <PaddingBox>
    <div class="mt-12 pb-12">
      <div class="flex justify-center">
        <div class="w-4/5">
          <h2 class="text-5xl text-center text-blue font-bold">
            Become One of A Hundred People to Invest This Month
          </h2>
        </div>
      </div>

      <p>
        Invest today to ensure you don’t lose access to advice that will add 20 to 40% to your
        income.
      </p>
      <p>I should be pricing this at $1,500.</p>
      <p>
        The return on the investment will be 20x that amount. (A $30,000/year increase divided by
        $1,500 = 20)
      </p>
      <p>Keep in mind:</p>
      <p>That 30% will stay with you year after year.</p>
      <p>
        So after five years of using this advice, you’ll have received over $150,000 of additional
        value by applying it over and over.
      </p>
      <p>That’s what happens if you change roles one time only.</p>
      <p>
        Suppose you change roles 2-3x over ten years, securing a $30,000 pay increase each time. By
        year 6 you’ll be earning an additional $60,000 per year.
      </p>
      <p>This guide could be priced at over $3,000 and still generate a 10x ROI for its users.</p>
      <p>Invest today and you’ll receive the complete guide for:</p>

      <!-- // big bold centered text -->
      <div class="w-full flex justify-center">
        <div class="text-center">
          <div>
            <h3 class="text-2xl">What I could charge: <span class="line-through">$3,000</span></h3>
          </div>
          <div>
            <h3 class="text-2xl">
              What I charge for a 1 on 1: <span class="line-through">$500</span>
            </h3>
          </div>
          <div><h3 class="text-2xl">Your investment: $87.</h3></div>
        </div>
      </div>
    </div>
  </PaddingBox>
</StandardBox>

<WideBox>
  <div class="px-4 sm:px-12 lg:px-24 xl:px-40 bg-celeste pt-8 pb-16">
    <h2 class="text-5xl text-blue font-bold text-center">
      A Guaranteed Return On Investment: Absolutely Zero Risk!
    </h2>

    <p>
      Provide screenshots proving you sent out 1,000 applications since investing in this service
      without getting responses. You’ll receive five free 1 on 1 sessions to examine what you’re
      doing well… and what needs work.
    </p>
    <p>I am able to offer this guarantee because the offer works and works well.</p>

    <p>You do the work to apply the advice.</p>
    <p>You send out your resume.</p>
    <p>You prove you did it.</p>
    <p>No results? No problem.</p>
    <p>
      I’ll give you five hours of my time across five weeks to show you exactly what you’ve done
      well… and what needs work.
    </p>
  </div>
</WideBox>

<StandardBox
  ><PaddingBox>
    <div class="mt-16">
      <!-- <div class="px-8 py-8 bg-coral"> -->
      <h2 class="text-center font-bold text-5xl">Get Your Resume Revamped Today (Or Miss Out)</h2>
      <!-- </div> -->

      <p>
        To ensure that these job hunting and negotiating techniques stay secret, I only offer this
        guide to a hundred people every month.
      </p>
      <p>That puts a severe limitation on how many are able to invest. It’s true.</p>
      <p>
        Yet I also want to avoid employers “seeing it coming” by recognizing these successful
        techniques when they first see them.
      </p>
      <p>
        Since you wouldn’t get much value out of it if every employer could counter these
        negotiation techniques, I have to avoid giving it out too often.
      </p>
      <p class="font-bold">There’s another reason you need to act now:</p>
      <p>
        <span class="font-bold"
          >If you let this opportunity pass by, you’ll have the same income next year…</span
        >
      </p>
      <p>And next year…</p>
      <p>And the next.</p>
      <p>You’ll continue to work with the knowledge that you are undervalued and underpaid.</p>
    </div>
  </PaddingBox></StandardBox
>

<StandardBox
  ><PaddingBox>
    <div class="mb-48">
      <p>Do you want this change?</p>
      <p>The people I’ve helped before you have told me:</p>
      <p>They’re glad to have changed, and enjoy their new life.</p>
      <p>Is this change right for you?</p>
      <p>If you’re unsure you want to start earning $20,000 or more additional dollars per year…</p>
      <p>Remember that you could get a raise this week by following my advice.</p>

      <div class="mt-8 w-full flex justify-center">
        <BigBeautifulButton />
      </div>
      <!-- // todo: insert direct link to cart on gumroad -->
    </div>
  </PaddingBox></StandardBox
>

<style>
  h2,
  h3 {
    margin-top: 28px;
    margin-bottom: 20px;
  }

  .list-with-bullets > li {
    list-style-type: disc;
    font-size: 20px;
  }

  .list-with-bullets-with-big-text > li {
    list-style-type: disc;
    font-size: 20px;
  }

  .question-text {
    font-size: 24px;
    font-weight: bold;
  }

  #faq-headline {
    padding-top: 40px;
    margin-bottom: 40px;
  }

  #secret-box-headline {
    margin-top: 48px;
  }

  .secret-text-sizing > p {
    font-size: 28px;
    margin-top: 20px;
  }

  p,
  li {
    font-size: 20px;
  }

  p {
    margin-top: 12px;
  }

  .mixed-group > * {
    margin-top: 18px;
  }

  .p-group > p {
    margin-top: 18px;
  }

  .persuasion-tool p {
    margin-top: 18px;
  }

  .text-off-white-container * {
    color: #e5eef5;
  }
</style>
