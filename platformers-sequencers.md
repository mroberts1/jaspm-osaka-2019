Platformers and Sequencers: Playing with MIDI 
LUDOMUSICOLOGY conference 2015 
Martin Roberts
game 
University of Derby 
 





music
toy














At what point does a game become a musical instrument, or a musical instrument a game? What is the relationship between a game, a musical instrument, and that often problematic category, at least for adults, a toy? These are some of the questions I have myself been toying with in recent years, both in theoretical and in practical terms, and which inform the present paper. Broadly speaking, I’m interested in the relationship between musical and gaming environments, and the increasing blurring of the lines between them over recent decades, or what may be schematically seen as the convergence of the three circles in the above diagram.

While music as a soundtrack has been a key component of video games since very early in their history, my particular interest here is in that much smaller category of games in which the generation of music is one of the main purposes, if not the main   purpose, of game play itself. Conversely, I’m also interested in the by now extensive field of what might be termed emergent musics, at least since John Cage, in which music is generated, often arbitrarily, from a set of game-like rules, from the Music of Changes to Conway’s Game of Life. On the current generation of mobile platforms, these game-music hybrids have proliferated in recent years in the form of the app, from Brian Eno’s adaptations of his ambient music projects to more complex mutations such as NodeBeat or Mixtikl - all, of course, now playable on your iPhone. 

A third and more recent dimension of the convergence between games and music involves a reversal of the generative hierarchy described above, with the generating not of music from games but of games from music, or more specifically from technologies of digital musical production. 

MIDI (Musical Instrument Digital Interface) technology, I will be suggesting in what follows, occupies a key position, not just in technical but also conceptual terms, at the interface between games and music today. While I don't intend to go into the history of MIDI since its origins in the 1980s, a brief clarification of what we're talking about may be useful at the outset. As Winifred Phillips describes in one of the most lucid recent accounts of the subject, MIDI is most easily understood as the digital descendant of the historical piano rolls and music boxes which were among the earliest forms of musical automation. It originated as a communication protocol enabling the digital capture of performance as data, not just in terms of note-events but also expressive elements such as velocity or sustain, which enabled the possibility of using the resulting MIDI file either to generate sound either from a hardware instrument such as a synthesizer, or, increasingly, from a virtual one in the sound library of a digital audio workstation. While MIDI remains a key part of the game composer's repertoire, as Phillips explains, it is only one of multiple tools which include LucasArts' iMUSE system, MOD files, and rendered audio files. MIDI's significance in the domain of electronic music production was that it in tandem with virtual instrument libraries and sequencers, it made it possible to produce music entirely on digital audio workstations, independently of the performance of musicians. It remains a fundamental element of electronic music production and its significance has arguably grown in recent years with the growth of iOS as a major music production platform and the plethora of MIDI-based music sofware which has accompanied it.

I want to begin by reviewing some historical prototypes of contemporary mutations in game-music hybridization, which given the expertise of this particular audience will presumably be familiar to a good number of people here today.  It will come as no surprise that Nintendo looms large in the historical timeline of game-music hybrids, most notably in the work of Toshio Iwai, whose career can be seen as in many ways located at the nexus between the three circles of game, music, and toy of my initial diagram. In the domain of digital music, Iwai is known primarily as the developer of a device known as the Tenori-on, a hand-held tone-matrix step-sequencer which in the late 1990s and early 2000s enjoyed a brief niche popularity among experimentally-inclined popular musicians, from Kieran Hebden (Fourtet) to Victoria Hesketh (Little Boots). In the gaming world, though, Iwai is better known as the creator of two games, Otocky (1987) and Electroplankton (2005) which are considered pioneering examples exploring the frontier between games and music, the idea of games as musical instruments, and vice versa. Otocky, described as “an improvisatory music-themed shoot-‘em up with a procedurally generated soundtrack”, was reportedly inspired by Iwai’s earlier experiments in using the arcade game Xevious and later Super Mario Bros. to play music. While Otocky was experienced more as a musical toy than a game proper, Electroplankton was more explicitly conceived as a “set of 10 small musical toys” drawing on biological metaphors for generating digital musical lifeforms. 

Interesting as each of these examples are, they arguably maintain a hierarchical relationship in which music remains internal and in a sense subordinate to the game environment. From this perspective the Tenori-on can be seen as a more radical experiment in that it goes further in blurring the boundaries between game, music and toy. Seeing and hearing the device for the first time created an ontological confusion in understanding what exactly it was: a new musical instrument? A new kind of game? A toy? Or all of the above? This confusion primarily involved the fact that it could be played in both senses of the term, both like a musical instrument and like a kind of abstract game in which initial parameters can be set and modified experimentally in real time, without a clear idea at the outset of their outcome. While as a piece of hardware the device was credible as a new kind of musical instrument, its subsequent migration to the platforms of mobile phones and tablets as software, in the form of Yamaha’s TNR-i iOS app, along with an entire generation of offspring apps inspired by it, positioned it more polymorphously as a musical game or toy that could be simultaneously played and played with in a kind of musical bricolage.

As mentioned earlier, the Tenori-on was essentially a step sequencer (or more precisely  a stack of sequencers layered on top of one another), a technology whose history is closely intertwined both with that of the synthesizer and with MIDI technology: from an early stage in their development, analogue synthesizers included on-board sequencers which enabled musical phrases (more commonly known as patterns) to be automated, layered, and chained together into songs. As standalone devices, however, sequencers could be used as MIDI controllers to generate such patterns from any connected synth module. What the Tenori-on did was in a sense to turn the relationship between the synth and the sequencer inside out, making the sequencer the primary instrument, so to speak, which could generate its own sequenced sounds. As with any such standalone device, however, these on-board sounds quickly proved to be very limited, at least compared to the possibilities of using the Tenori-on as a MIDI controller for more high-end synths. At this point, however, the whole raison d'être for the Tenori-on collapsed, since any sequencer could do pretty much the same thing. With the advent of the iPad and a new generation of MIDI sequencer apps (Cubasis, Genome, Modstep), even the Tenori-on’s appeal as a hand-held device became irrelevant, making it today perhaps the first vintage instrument of the new century.

While standalone sequencers today are still being produced (IMAGE: Korg SQ-1), like the Tenori-on they have largely migrated to software platforms, and are today a staple of digital audio workstations. A digital sequencer’s interface may take many different forms, but typically consists of a two-dimensional screen displaying arrays of MIDI notes corresponding to a piano keyboard, (each of which may be inflected by parameters such as velocity, sustain, etc.), across which a vertical playhead moves from left to right. As the playhead moves, the screen either scrolls from right to left to follow it, or jumps to the next pattern in the song. Music can be generated in real time by turning MIDI notes on or off at specific points in a pattern, a function often referred to as “MIDI draw” because of its similarity to the process of drawing. 

To any gamer, the scrolling MIDI interface, with its clusters of platform-like notes and continuous movement from right to left, is structurally similar to that most beloved of game genres, the scrolling platform game, perhaps most iconically embodied by Super Mario Bros. As with electronic music production today, game programming is very much a matter of sequencing, and the intricate coordination of graphical with musical objects. Adding music to games is in large part a matter of synchronizing graphical timelines with musical, MIDI-based ones so that in-game events trigger corresponding note-events at the appropriate moment.

The structural affinity between MIDI interfaces and game environments is by no means limited to scrolling platform games, however. One MIDI interface popular in piano-teaching apps is the downward-scrolling “waterfall” interface, in which clusters of notes progress vertically down the screen and sound when they meet a static playhead represented by a standard piano keyboard. While clearly inspired by piano-roll and music-box interfaces, the interface again evokes the familiar downward mobility of classic arcade games. The two metaphors are neatly brought together in a note-teaching game developed for MacOS and PC by David Bagno which is actually called Musical Space Invaders. [IMAGE] It’s been suggested, in this context, that the so-called  “impossible music” of the notorious Black MIDI subculture was at least partly inspired by an extreme variant of the shoot-‘em up genre known as “bullet hell” games, in which the player is similarly overwhelmed by an equally "impossible" hail of bullets raining down from an enemy, which can only be escaped by learning their patterns and trajectories through them through a long process of trial and (mainly) error. [IMAGES]

Given the structural affinities between MIDI interfaces and gaming environments, it was only a matter of time before the idea arose not of generating music within a gaming environment but of turning the MIDI interface itself into a platform game, or even generating game elements from potentially any MIDI file of a piece of music. Some interesting examples are provided by Lemur, a highly customisable MIDI controller for the iPad (and now Android) which enables the user to design their own interface into templates, by selecting from a repertoire of digital objects such as sliders, buttons, knobs, bouncing balls which can be mapped to MIDI programme numbers, and menus, laid out on a two-dimensional field called a canvas. The term "bouncing balls" may have caught your attention in the above list, and Lemur also incorporates what is called a physics engine, which simulates effects such as "gravity" or "friction" on the balls' movement. From here the requisite MIDI template of the 1972 proto-game Pong becomes an inevitability, with the only interesting question being whether it also uses the iPad's accelerometer (the answer, to my knowledge, is not at this point, although other music-based games for iOS do). Another Lemur template offers a musical adaptation of Flappy Bird. Rudimentary as such examples may be, they at least hint at some of the possibilities of MIDI interfaces as game environments.

By far the most radical and ingenious exploration of MIDI as a game space to date is game composer Will Bedford's wittily titled game The Adventures of General MIDI (a punning reference to the General MIDI protocol which ensures consistency of sounds in files played on different MIDI instruments). Developed in Apple's Logic Pro digital audio workstation, the game uses the MaxMsp visual programming language and Javascript to generate game platforms and objects, including characters and their behaviour, from data from inputted MIDI files. [CLIP] 

Although an experimental project not on general release, the game raises some intriguing ludomusicological questions, not least because it offers the possibility of being able to "play" a song in more than just the conventional ways (playing as listening; playing as musical performance): just as one might import a MIDI file of, say, Donkey Kong, one might also try "playing" Debussy's "Arabesques" or Deep Purple's "Highway Star". This in turn raises further questions concerning the use of MIDI data as, in effect, a game engine: clearly some songs, or even entire genres, whatever their own particular merits, may not generate particularly interesting game experiences, and vice versa. My own contribution of a MIDI file of one of Conlon Nancarrow's player-piano pieces, for example, for all its theoretical interest, apparently did not produce a particularly satisfying game experience, even though part of the "game", in this case, seems to include the meta-gaming pleasure of coming up with intriguing ideas for MIDI files to "play" as a side-scrolling platformer.

A less geeky and more commercial application of Bedford's MIDI-game concept is the iOS game Wave Trip (2012), developed by the Scottish studio Lucky Frame. In some ways an update of Toshio Iwai's Otocky as a side-scrolling music game-toy, the game is also closer to some of the more recent experiments I've just been discussing in that it offers the player/user a creative role in building his/her own levels, by selecting from a repertoire of musical and sound objects and obstacles, and positioning them as MIDI-like notes on a sequence of pattern canvases, which are then triggered (or not) by the flying character-playhead as it moves through them. As with other subcultural musical communities which have mushroomed in recent years around sharing Tenori-on songs or Wii music videos, Wave Trip is clearly conceived with a social media audience in mind in that new levels can be shared with the larger game community.

As MIDI and other controller interfaces continue to develop, we can surely expect more complex experiments than the examples reviewed here, especially in environments such as Lemur and MaxMSP. I want to conclude, however, by mentioning a potentially more radical convergence of music and gaming resulting from that between immersive technologies, new gestural interfaces, and new animated musics. Current experiments involving the Leap Motion touchless controller and the Oculus Rift next-gen virtual reality simulator hint at a near future in which the player-musician may increasingly take on the role of the controlling and coordinating the interaction and behaviours of increasingly complex musical characters and objects in virtual spaces. Yamaha's "virtual idol" Hatsune Miku, secondly, a voice synthesizer and sequencer embodied in a digital character whose dance moves as well as voice can be sequenced like MIDI data, suggests a different future of musical role-playing games. Today we may can "play" Hatsune Miku and her digital companions in the music videos which have taken the Japanese music industry by storm in recent years; tomorrow, we may be able to "play" her in the more direct sense of remote-controlling her virtual performance with our own. Virtual karaoke, anyone? Now that the telekinetic, disembodied musics long dreamed of by Kraftwerk and the Yellow Magic Orchestra finally seem within our grasp, they have never seemed more timely; perhaps this is why they continue to fascinate.


 


























