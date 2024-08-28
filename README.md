<!DOCTYPE html>
<html>
    <head>
        <title>Youtube</title>
        <link rel="stylesheet" href="youtube.css">
        <link rel="stylesheet" href="header.css">
        <link rel="stylesheet" href="general.css">
        <link rel="stylesheet" href="sidebar.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    </head>
    <!--HEAD-->

    <!--BODY-->
    <body>
        <!--HEADER-->
        <header class="header">
            <div class="left-section"> 
                <img src="thumbnails/header_thumbnails/hamburger-menu.svg" class="hamnurger-menu">
                <img src="thumbnails/header_thumbnails/youtube-logo.svg" class="youtube-logo">
            </div>
            <div class="middle-section">
                <input type="text" placeholder="Search" class="Searchbar">
                <button class="search-button"> <img src="thumbnails/header_thumbnails/search.svg" class="search-icon">
                <div class="tooltip">search </div>
                </button>
                <button class="voice-search"> <img src="thumbnails/header_thumbnails/voice-search-icon.svg" class="voice-icon">
                    <div class="tooltip">Search with your voice</div>
                </button>

            </div>
            <div class="right-section">
                <div class="upload-icon-container">
                    <img src="thumbnails/header_thumbnails/upload.svg" class="upload">
                    <div class="tooltip">Create</div>
                </div>
                <div class="youtubeapps-icon-container"><img src="thumbnails/header_thumbnails/youtube-apps.svg" class="upload">
                    <div class="tooltip">YouTube apps</div>
                </div>
                <div class="notification-icon-container">
                    <img src="thumbnails/header_thumbnails/notifications.svg" class="notification-icon">
                    <div class="tooltip">Notifications</div>
                    <div class="notification-count" >3</div>
                </div>
                <div class="profile-icon-container"><img src="thumbnails/header_thumbnails/hqdefault.jpg" class="dp"></div>
                

                
            </div>
        </header>
        <!--SIDEBAR-->
        <nav class="sidebar">
            <div class="sidebar-link">
                <img src="thumbnails/sidebar_thumbnails/home.svg" class="sidebar-icon" >
                <div>Home</div>
            </div>
            <div class="sidebar-link">
                <img src="thumbnails/sidebar_thumbnails/explore.svg" class="sidebar-icon">
                <div>Explore</div>
            </div>
            <div class="sidebar-link">
                <img src="thumbnails/sidebar_thumbnails/subscriptions.svg" class="sidebar-icon">
                <div>Subscriptions</div>
            </div>
            <div class="sidebar-link">
                <img src="thumbnails/sidebar_thumbnails/originals.svg" class="sidebar-icon">
                <div>Originals</div>
            </div>
            <div class="sidebar-link"> 
                <img src="thumbnails/sidebar_thumbnails/youtube-music.svg" class="sidebar-icon">
                <div>Youtube Music</div>
            </div>
            <div class="sidebar-link">
                <img src="thumbnails/sidebar_thumbnails/library.svg" class="sidebar-icon">
                <div>Library</div>
            </div>
        </nav>
        <!--MAIN-->
        <main>
            <section class="display-grid">
                <!--videos-->
                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-1.webp" ></a>
                        <div class="time">14:20</div> 
                    </div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/c/mkbhd"><img src="thumbnails/channel-thumbnail/channel-1.jpeg" class="channel"></a> 
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-1.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>Marques Brownlee</p>
                                        <p class="channel-hover-subs">19.3M subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                Talking Tech and AI with Google CEO Sundar Pichai!
                            </p>
                            <p class="videocreator">
                                Marques Brownlee
                            </p>
                            <p class="videoinfo">
                                3.4M views · 6 months ago
                            </p>
        
                        </div>
                    </div>
                </div>
                <!--END-->
        
                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-2.webp" > </a><div class="time">8:22</div></div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/c/markiplier"><img src="thumbnails/channel-thumbnail/channel-2.jpeg" class="channel"></a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-2.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>Markiplier</p>
                                        <p class="channel-hover-subs">36.9 subscribers</p>
                                    </div>
                                </div>
                            </div> 
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                Try Not To Laugh Challenge #9
                            </p>
                            <p class="videocreator">
                                Markiplier
                            </p>
                            <p class="videoinfo">
                                19M views · 4 years ago
                            </p>
        
                        </div>
                    </div>
                </div>
    
                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=JhpP1nX1xQM"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-3.webp" ></a> <div class="time">11:31</div></div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@penguinz0"><img src="thumbnails/channel-thumbnail/channel-3.jpeg" class="channel"></a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-3.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>penguinz0</p>
                                        <p class="channel-hover-subs">15.8M subscribers</p>
                                    </div>
                                </div>
                            </div> 
                         
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                I Used to Hate This                            </p>
                            <p class="videocreator">
                                penguinz0</p>
                            <p class="videoinfo">
                                1.2M views · 5 days ago
                                
                            </p>
        
                        </div>
                    </div>
                </div>
        
                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=kSt2QspMnG0"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-4.webp" ></a><div class="time">21:05</div> </div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@PewDiePie"> <img src="thumbnails/channel-thumbnail/channel-4.jpeg" class="channel"> </a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-4.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>
                                            PewDiePie
                                        </p>
                                        <p class="channel-hover-subs">111M subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                MAYBE
                            </p>
                            <p class="videocreator">
                                PewDiePie
                            </p>
                            <p class="videoinfo">
                                1.3M views · 1 day ago
                            </p>
        
                        </div>
                    </div>
                </div>
    
                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=uz2m_k6L1q4"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-5.webp" ></a> <div class="time">11:17</div></div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@CrimsonDesert"> <img src="thumbnails/channel-thumbnail/channel-5.jpeg" class="channel"> </a> 
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-5.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>Crimson Desert</p>
                                        <p class="channel-hover-subs">57.5k subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                Crimson Desert – Reed Devil Boss Battle Gameplay |...
                            </p>
                            <p class="videocreator">
                                Crimson Desert
                            </p>
                            <p class="videoinfo">
                                1.1M views · 5 days ago
                            </p>
        
                        </div>
                    </div>
                </div>
        
                <div class="videocard">
                    <div class="thumbnail-row"><a href="https://www.youtube.com/watch?v=yXWw0_UfSFg"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-6.webp" ></a>  <div class="time">19:59</div></div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@MrBeast"> <img src="thumbnails/channel-thumbnail/channel-6.jpeg    " class="channel"> </a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-6.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>
                                            MrBeast
                                        </p>
                                        <p class="channel-hover-subs">312M subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                Anything You Can Fit In The Circle I’ll Pay For
                            </p>
                            <p class="videocreator">
                                MrBeast
                            </p>
                            <p class="videoinfo">
                                19M views · 4 years ago
                            </p>
        
                        </div>
                    </div>
                </div>

                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=XqTwwZCa1_Y"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-7.webp" ></a>
                        <div class="time">2:21</div> 
                    </div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@SivakarthikeyanProductions"> <img src="thumbnails/channel-thumbnail/channel-7.jpeg" class="channel"></a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-7.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>Sivakarthikeyan Productions</p>
                                        <p class="channel-hover-subs">225k subscribers</p>
                                    </div>
                                </div>
                            </div>
                         </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                Kottukkaali - Making of the Interval | Featurette - E3 | Soori | Anna Ben | PS...
                            </p>
                            <p class="videocreator">
                                Sivakarthikeyan Productions
                            </p>
                            <p class="videoinfo">
                                14,485 views · 20 hours ago
                            </p>
        
                        </div>
                    </div>
                </div>

                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=GoAA0sYkLI0&t=79s"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-8.webp" ></a>
                        <div class="time">17:34</div> 
                    </div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@VanityFair"> <img src="thumbnails/channel-thumbnail/channel-8.jpeg" class="channel"> </a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-8.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>Vanity Fair</p>
                                        <p class="channel-hover-subs">4.36M subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                ‘Dune’ Director Denis Villeneuve Breaks Down a Scene | Vanity Fair</p>
                            <p class="videocreator">
                                Vanity Fair
                            </p>
                            <p class="videoinfo">
                                4.9M views · 2 years ago
                            </p>
        
                        </div>
                    </div>
                </div>

                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=HfoU_Z1uVfc&t=257s"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-9.webp" ></a>
                        <div class="time">8:12</div> 
                    </div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@SpikimaMovies"> <img src="thumbnails/channel-thumbnail/channel-9.jpeg" class="channel"></a> 
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-9.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>Spikima Movies</p>
                                        <p class="channel-hover-subs">7.7M subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                Kairo | Anatomy Of The Scariest Scene Ever
                            </p>
                            <p class="videocreator">
                                Spikima Movies
                            </p>
                            <p class="videoinfo">
                                7.7M views · 4 years ago
                            </p>
        
                        </div>
                    </div>
                </div>

                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=mugLOcqpGYw"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-10.webp" ></a>
                        <div class="time">10:03</div> 
                    </div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@KarstenRunquist"> <img src="thumbnails/channel-thumbnail/channel-10.jpeg" class="channel"> </a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-10.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>Karsten Runquist </p>
                                        <p class="channel-hover-subs">699K subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                why bojack horseman's finale is perfect
                            </p>
                            <p class="videocreator">
                                Karsten Runquist  
                            </p>
                            <p class="videoinfo">
                                624K views · 4 years ago
                            </p>
        
                        </div>
                    </div>
                </div>

                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=RMNjO-rFGX4"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-11.webp" ></a>
                        <div class="time">2:46</div> 
                    </div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@TheNubKnight"> <img src="thumbnails/channel-thumbnail/channel-11.jpeg" class="channel"> </a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-11.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>KnubNight </p>
                                        <p class="channel-hover-subs">3.38K subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                "just let it happen"
                            </p>
                            <p class="videocreator">
                                KnubNight
                            </p>
                            <p class="videoinfo">
                                438K views · 3 weeks ago 
                            </p>
        
                        </div>
                    </div>
                </div>

                <div class="videocard">
                    <div class="thumbnail-row"> <a href="https://www.youtube.com/watch?v=tI_DiRyU0OA"> <img class="vediothumbnail" src="thumbnails/video-thumbnail/thumbnail-12.webp" ></a>
                        <div class="time">4:58</div> 
                    </div>
                    <div class="videogrid">
                        <div class="channelthumbnail"> <a href="https://www.youtube.com/@Absurdyssey2002"><img src="thumbnails/channel-thumbnail/channel-12.jpeg" class="channel"> </a>
                            <div class="channel-hover-container">
                                <div class="channel-hover-container-info">
                                    <div class="channel-hover-thumbnail-container"><img src="thumbnails/channel-thumbnail/channel-12.jpeg" class="channel-hover-thumbnail"></div>
                                    <div class="channel-hover-name-subs-container">
                                        <p class=channel-hover-name>Absurdyssey </p>
                                        <p class="channel-hover-subs">4.51K subscribers</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="channelinfo">
                            <p class="videotitle">
                                Do not gaze into the Abyss | Nietzsche
                            </p>
                            <p class="videocreator">
                                Absurdyssey
                            </p>
                            <p class="videoinfo">
                                264K views · 4 months ago
                            </p>
        
                        </div>
                    </div>
                </div>
            </section>
        </main>
        <footer style="height: 50px;"></footer>
        
        
    </body>
</html>
