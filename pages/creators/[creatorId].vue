<template>
    <div class="ml-[160px]" >
        <div v-if="creatorId == 'SsethTzentach'" class="header flex items-center border-b-2 border-black mb-[10px] mr-[10px]">
            <div class="datext">
                <h1 class="text-[70px] font-medium ">{{ creatorId }}</h1> 
            </div>
            <div class="dapics ml-auto">
                <img class="h-[100px] ml-auto border-2 border-white rounded-lg shadow-lg" src="https://scontent.fcgk8-2.fna.fbcdn.net/v/t39.30808-1/297893906_602139911272037_100711993481514336_n.jpg?stp=dst-jpg_p200x200&_nc_cat=107&ccb=1-7&_nc_sid=c6021c&_nc_ohc=jDLXEuh7NPUAX-WWTVy&_nc_ht=scontent.fcgk8-2.fna&oh=00_AfBMud1_eDiHOOlWq2wEADjIiXCz2JS48x8UYqX9cAILWw&oe=6467D3C3" alt="">
            </div>
           
        </div>

        <div v-if="creatorId == 'Albino'" class="header flex items-center border-b-2 border-black mb-[10px] mr-[10px]">
            <div class="datext">
                <h1 class="text-[70px] font-medium ">{{ creatorId }}</h1> 
            </div>
            <div class="dapics ml-auto">
                <img class="h-[100px] ml-auto border-2 border-white rounded-lg shadow-lg" src="https://yt3.googleusercontent.com/ytc/AGIKgqMRhc2T1qMdPElVV4VA0R7nZTDaI53-6OA9nDPreg=s176-c-k-c0x00ffffff-no-rj" alt="">
            </div>
           
        </div>

        <div v-if="creatorId == 'Max0r'" class="header flex items-center border-b-2 border-black mb-[10px] mr-[10px]">
            <div class="datext">
                <h1 class="text-[70px] font-medium ">{{ creatorId }}</h1> 
            </div>
            <div class="dapics ml-auto">
                <img class="h-[100px] ml-auto border-2 border-white rounded-lg shadow-lg" src="https://yt3.googleusercontent.com/ytc/AGIKgqPi0LioT8O_Xx4xs6dJPhm6CXWYaqBy8JVJvHdbQQ=s176-c-k-c0x00ffffff-no-rj" alt="">
            </div>
           
        </div>

        <div v-if="creatorId == 'Huggbees'" class="header flex items-center border-b-2 border-black mb-[10px] mr-[10px]">
            <div class="datext">
                <h1 class="text-[70px] font-medium ">{{ creatorId }}</h1> 
            </div>
            <div class="dapics ml-auto">
                <img class="h-[100px] ml-auto border-2 border-white rounded-lg shadow-lg" src="https://yt3.googleusercontent.com/ytc/AGIKgqMh5Lv0jAxa48F0jcvqw9oAfvj00WywPgGCeWS4eg=s176-c-k-c0x00ffffff-no-rj" alt="">
            </div>
           
        </div>
        
        <div v-if="creatorId == 'SsethTzentach'" class="">
            <p class="text-[20px] mb-[10px]">SsethTzeentach /sɛθ.ziːn.tæk/ is a YouTuber who has been active since late
                2007. He makes comedic reviews of video games.
            </p>
            <p class="text-justifiy indent-10 mb-[20px]">Sseth started his career with posting League of Legends videos,
                however he deviated from this niche by making
                his iconic Might and Magic VI review in 2014. Meme-laden and humorously edited reviews of games has since
                become his main videos on his channel, although many of said games that he reviews are enjoyed by him to the
                point that he is willing to passionately recommend them to his viewers and goes as far as to give
                installation advice and his personal game keys. In his early 2019 review of Dwarf Fortress, he declared that
                he had left his medical job so that he could work full time on his YouTube channel.

                The humor in his videos has frequently been described as something originating from 4Chan, having made jokes
                and satirical potshots against most of the controversial groups of people in the world. He has called
                himself a Manchild on several occasions and many of his videos have crossed the line at least twice. Indeed,
                many of his early videos are crammed with so many cropped and edited NSFW images, freeze frames, and memes
                straight from /v/ that it's not unexpected for multiple viewings to be needed in order to spot all of the
                jokes and references.

                Some of his reviews such as Kenshi, Space Station 13, and Starsector have brought large amounts of new
                players flocking towards their forums and games, and has gotten to the point where some of the developers
                have explicitly acknowledged him.</p>
        </div>
        <div v-if="creatorId == 'Albino'" class="mr-[10px]">
                <p class=" text-[20px] mb-[10px]">
            AlbinoVEVO is a 27-year-old YouTuber who plays games like The Binding of Isaac, Risk of Rain 2, Rainworld,
            and Splunky. He is known as PewDiePie in areas like the U.S.A. He is a preacher of the one god we know as
            Neco Arc, spreading her beliefs through out the land.
            </p>
            <p class="text-justifiy indent-10 mb-[20px]">
                [REDACTED]
            </p>
        </div>
        <div v-if="creatorId == 'Max0r'" class="mr-[10px]">
                <p class=" text-[20px] mb-[10px]">
            Whether it's highly edited narration, funny dubbing, or in-game moments, I have you covered on the full
            spectrum of stupid.
            </p>
            <p class="text-justify indent-10 mb-[20px]">
                Max0r is a YouTuber known for comedically reviewing and summarizing various video games, ranging from
                Neopets to Metal Gear Rising: Revengeance. He has become very well known across the internet thanks mostly
                in part to the rise of Metal Gear Rising: Revengeance memes during early 2022, with segments of his summary
                of the game being very well spread, particularly in discord meme channels, as well as the joke in his
                Genshin Impact review reminding players that 'the age of consent is 18'. His humour generally consists of a
                combination of random=funny, references to currents memes and trends, dark humour, generally depicting
                characters or actions as far more despicable and vile than they actually are while constantly insisting that
                he's "normal" and his signature fast paced editing combined with psychedelic effects, a style that has been
                described by many as 'the best way to find out if you have epilepsy.'
            </p>
        </div>
        <div v-if="creatorId == 'Huggbees'" class="mr-[10px]">
            <p class="text-[20px] mb-[10px] text-justify">
                Andrew Wagenheim (born: November 10, 1991 [age 31]), better known online as Huggbees (previously known as
                TheLoneN00b), is an American YouTuber and Twitch streamer residing in Tampa, Florida, United States who is
                mostly known for his streams and comedic parodies on educational television shows.
            </p>
            <p class="text-justify indent-10 mb-[20px]">
                Andrew joined YouTube as The Lone N00b in September 28, 2006. Despite not uploading until 2014, he would
                appear on Cr1TiKaL's, GeePM's,and Vinesauce's streams throughout the early 2010s which gained traction to
                his at the time inactive channel.

                In June 6, 2014, Andrew uploaded his first video I Am The Night. The video is a scene from some old puppet
                show (presumably from the 90's) where a puppet sings "I am the night" with background singers. In July 27,
                2016, he changed his channel name to Huggbees and uploaded his second video The Violent Sexsplosion Known As
                H-Doom, a gameplay video of a DOOM porn parody. He has since been actively uploading videos.

                On April 20, 2018, he uploaded the first How It's Actually Made video on the chocolate episode of the TV
                series. He has since been doing edutainment parodies mixed in with variety gaming videos and vlogs.
            </p>
        </div>
    </div>
</template>

<script setup>
const { creatorId } = useRoute().params
</script>

<style scoped></style>