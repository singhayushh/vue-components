<template>
    <section>
        <div class="span-1-of-2">
            <div class="contain">
                <h1>You can cook a pizza on the windowsill in nine seconds.</h1>
                <p>There are thousands of asteroids whose orbit in the Solar System crosses that of Earth. And we have a little acronym for them. And next time my fans eat pizza, they're thinking of Venus! </p>
                <Button text="Try deGrasse for Free"/>
            </div>
        </div>
        <div class="span-1-of-2 flex">
            <div class="img-wrapper flex">
                <img src="../../../public/main.svg" alt="">
            </div>
        </div>
    </section>
    <section class="white-bg">
        <div class="span-1-of-2 flex">
            <div class="img-wrapper flex">
                <img src="../../../public/main.svg" alt="">
            </div>
        </div>
        <div class="span-1-of-2 flex">
            <div class="contain short-text">
                <h2>The people who don't ask questions remain clueless throughout their lives. </h2>
                <p>There is always a place I can take someone's curiosity and land where they end up enlightened when we're done. That's my challenge as an educator. No one is dumb who is curious.</p>
                <Button text="Try deGrasse for Free"/>
            </div>
        </div>
        <div class="span-1-of-1 grey-bg">
            <div class="contain">
                <div class="text-wrapper">
                    <h4>Spacer</h4>
                    <p class="short-text">
                        When Kennedy said, 'Let's go to the moon,' we didn't yet have a vehicle that wouldn't kill you on launch. He said we'll land a man on the moon in eight years and bring him back. That was an audacious goal to put forth in front of the American people. 
                        If God is the mystery of the universe, these mysteries, we're tackling these mysteries one by one. If you're going to stay religious at the end of the conversation, God has to mean more to you than just where science has yet to tread.
                        The problem is not scientifically illiterate kids; it is scientifically illiterate adults. Kids are born curious about the natural world. They are always turning over rocks, jumping with two feet into mud puddles and playing with the tablecloth and fine china</p>
                </div>
            </div>
        </div>
    </section>
    <section class="white-bg">
        <div class="span-1-of-2 flex">
            <div class="contain short-text">
                <h2>They are gonna squash the creativity that would manifest itself.</h2>
                <p>Because they're clueless about what it and why it matters. But science can always benefit from the more brains there are that are thinking about it - but that's true for any field.</p>
                <Button text="Try deGrasse for Free"/>
            </div>
        </div>
        <div class="span-1-of-2 flex">
            <div class="img-wrapper flex">
                <img src="../../../public/main.svg" alt="">
            </div>
        </div>
        <div class="span-1-of-3 flex">
            <div class="flex card">
                <div class="text-wrapper">
                  <h4>deGrasse 1</h4>
                  <p>The universe is hilarious! Like, Venus is 900 degrees. I could tell you it melts lead</p>
                </div>
            </div>
        </div>
        <div class="span-1-of-3 flex">
            <div class="flex card">
                <div class="text-wrapper">
                  <h4>deGrasse 2</h4>
                  <p>But that's not as fun as saying, 'You can cook a pizza on the windowsill in nine seconds.'</p>
                </div>
            </div>
        </div>
        <div class="span-1-of-3 flex">
            <div class="flex card">
                <div class="text-wrapper">
                  <h4>deGrasse 3</h4>
                  <p>And next time my fans eat pizza, I can't imagine they're thinking of Venus! </p>
                </div>
            </div>
        </div>
        <div class="span-1-of-1"></div>
    </section>
</template>

<script>
import Button from '../ui/Button'

export default {
    name: 'HomePage',
    components: {
        Button,
    }
}
</script>

<style scoped>
p {
    margin: auto;
    margin-top: 1rem;
    margin-bottom: 2rem;
}

.img-wrapper {
    padding: var(--var-padding-l) 0;
}

.span-1-of-1 .text-wrapper {
    padding: 0 var(--var-padding-m);
}

.img-wrapper img {
    width: 80%;
}
</style>