define m = Character("Milo")
define p = Character("[player_name]")  
define e = Character("Nameless")
define n = Character("naomi")

label start:
    scene funeral with fade
    $ player_name = renpy.input("What's your name?: ")
    $ player_name = player_name.strip()  


    if not player_name:
        $ player_name = "Player"
    p "Clearly, they went too far this time."
    p "Whoever 'they' are."
    p "There's a bullying problem at our school."
    p "Marie is the most extreme example."
    p "But for me, the most important person in my life had to run away."
    p "Naomi... I'll find whoever's causing this and put an end to it."
    show naomi
    p "Where did you go? Where do I look to find you?"
    hide naomi

    p "Most everyone from the school showed up and left the moment they could, but the perpetrators with a conscience remained."
    p "A girl stood against the wall looking down."
    scene funeral2
    show milodown
    p "...She's so beautiful. There's no way she doesn't know anything."
    p "Okay, here goes..."
    p "'You're still here too? Do you mind if I sit next to you?'"
    e "..."
    p "I guess she's not in the mood to talk."
    p "The uncomfortable silence is continuing. I need to say something."
    hide milodown
    show milotalking
    e "'Were you close with her?'"
    hide milotalking
    show miloneutral
    p "That surprised me. I didn't expect her to initiate."
    p "'She was my everything. I don't know what to do without her.' Of course, I wasn't actually close to her, I needed to say what I thought she wanted to hear."
    hide miloneutral
    show milosad
    p "The look on her face startled me."
    e "'I'm so sorry.'"

    p "This must be guilt...?"
    p "'What about you? Were you close with her?'"
    hide milosad
    show milodown
    p "Nameless looks down"
    p "Guilt. Perfect."
    p "'It's okay, it's probably hard to talk about right now. Don't push yourself.'"
    p "I continued, 'She was very quiet about her personal life. I knew she was having a hard time. I just didn't know it was that bad.'"
    hide milodown
    show milosad
    p "I decided I'd put on my best performance and started to force any semblance of tears out."
    hide milosad
    p "A... hug??"
    m "Sniffle... sniffle..."
    p "She's even crying?"
    p "What kind of person is she to be so crushed by guilt?"
    show milosad
    p "I looked her in the eye. 'My name is [player_name]. I was thinking that maybe it would be some consolation to be friends.' I looked at her with pleading eyes."
    hide milosad
    show milosmiling
    hide milosmiling
    show milohappytalking
    m "Milo, I'm Milo. Nice to meet you [player_name]. Of course, give me your phone. I'll type in my number."
    hide milohappytalking
    show milobigsmile
    hide milobigsmile

    scene neutral with fade
    m "'[player_name] do you want to get coffee with me?'"
    p "I stared at my phone."
    p "A month has passed, and Milo has texted me every single day."
    p "Little progress was being made, but I knew that I'd have everything I needed by the time school began again. Either way, Milo was pleasant company."
    p "But the more I got to know Milo, the less passion I felt toward my initiative. I was becoming jaded."
    show naomi
    p "Naomi... I need my gaze to be fixed. I need to see nothing but you."
    hide naomi
    p "But I really did want to get coffee with her!"

    scene cafe with dissolve
    show milohappytalking
    m "'I got you something!'"
    m "'You commented on this top the last time we were at the mall. I thought I'd buy it for you.'"
    hide milohappytalking
    show milobigsmile
    p "Is her persona really this impressive?"
    p "'Milo... you're so kind.'"
    hide milobigsmile
    show milodown
    hide milodown
    show milotalking
    m "'Maybe this is a little unfair. I might be using you as redemption.'"
    m "'Don't think so highly of me, okay?'"
    hide milotalking
    show miloneutral
    p "Milo often hinted at the darkness of her past. This implied she was different now, that she was no longer an alleged cruel person. I would find out soon enough."
    p "Naomi saved me. We bonded over shared suffering. Both our mothers had died, and when my mom died, she visited me every day. She was one year older than me, she was like a big sister."
    p "If I'm lucky... Naomi might come back."

    p "Either way, I still didn’t have much of a plan. I had thought I’d understand what to do the more I got to know her. I had thought she’d be an easy person to hate."
    p "I had thought some way or another, I’d latch onto whoever was responsible with everything I had, and eventually have enough power to reduce her to nothing."
    p "Now I'm not so sure."
    p "Do you have any regrets, Milo?"
    show milodown
    m "..."
    p "Milo?"
    hide milodown
    show milotalking
    m "'I'll tell you one day, Milo. But I'd like to enjoy the peace a little longer, okay?'"
    hide milotalking
    p "I wondered how she expected me to take that. She was implying the truth would cause irreparable damage. Wouldn't that be enough to scare me away?"
    "'Whatever it is, we can overcome it, okay?'"
    show milosmiling
    p "Milo didn't say anything and just smiled."
    p "I don't think she believed it."
    hide milosmiling
    scene neutral
    p "And there, the peace continued. I must have lost sight of my goal the moment she embraced me."
    scene milos
    show milotalking
    m "'School is going to start up again soon. I even had a nightmare about it.'"
    p "'What are you so worried for? Everybody must love you.'"
    show milohappytalking
    m "'You think so!! I must be super likable, huh?'"
    p "'Maybe you should be a little more humble about it.'"
    hide milohappytalking
    show milobigsmile
    p "Milo laughed. She really was enchanting."
    hide milobigsmile
    show milohappytalking
    m "'I'm just happy that you think of me that way. That's all that matters to me.'"
    p "I blanked out and didn't respond. She's so forward with her thoughts. I forgot to even consider her being a bad person at this point."
    m "'Well anyway, maybe that means I have a chance. I don't think I can avoid it anymore. That's probably why I'm having nightmares anyhow.'"
    p "'Avoid... what?'"
    hide milohappytalking
    show milodown
    hide milodown
    show milotalking
    m "'The girl who committed suicide at the end of the year. Well... We were never friends. Actually, I was part of the problem.'"
    m "'I think about it every day. I was so weak...'"
    hide milotalking
    show milodown
    hide milodown
    show milotalking
    m "'Weak enough to lie to you after all. I just wanted to feel better. You were her friend, and I felt maybe I could redeem myself through you.'"
    m "'But I love you. I've never formed a connection like I have with you. I couldn't live with myself anymore knowing she was your everything, and I ruined that.'"
    hide milotalking
    show milosad
    hide milosad
    show milotalking
    m "'I thought I could become your everything as well. I'm so sorry.'"
    hide milotalking
    show milosad
    p "Suddenly, everything came rushing back to me. That's right. In a sense, she did take away my everything. But at the same time, she became my everything as well."
    p "What... am I supposed to do?"
    p "'It... you're a bully?'"
    p "How could I even be in disbelief right now?"
    hide milosad
    show milotalking
    m "'I'm so sorry. I didn't know how to escape it. She pressured me. She put me on a pedestal and manipulated my actions.'"
    p "'She?'"
    m "'There's this girl. Everyone looks up to her. She's all-powerful. Please, I didn't know it would be this hard. I don't want to lose you.'"
    p "For moments, I stared in disbelief, dissociated from the world around me."
    p "I knew this from the beginning, right?"
    hide milotalking
    show milodown
    p "My world became a spinning void. I couldn't latch onto anything cohesive."
    p "'You're the reason... Naomi left?'"
    hide milodown
    show milotalking
    m "'Naomi?'"
    p "'She stopped going to school. She hasn't messaged me in months. Where is she?!'"
    m "'I... I'm not sure. Naomi... She must have been Marie's close friend.'"
    p "'The girl who died?'"
    m "'There was this girl, always with Marie. She was never targeted. She actually had a lot of friends. Including the girl who pushed her to suicide.'"
    p "'Naomi would never.'"
    m "'Maybe she felt guilty as well. [player_name], I don't know. I'm just sorry'"
    hide milotalking
    show milosad
    p "Milo looked at me, her eyes begging for forgiveness. My heart sank in my chest."
    p "How do I feel right now? What does this mean for me?"
    p "Do I feel... relieved? After everything, I simply just have questions."
    p "Am I so simple that as long as I have someone to latch onto, it doesn't even matter who?"

    menu:
        "Forgive Milo":
            p "'Let's figure this out.'"
            p "If I lose you too, then what do I have left?..."
            p "'we'll fix everything together, okay?'"
            show milosmiling
            m"'Okay.'"

            return
        
        "Don't forgive Milo":
            
            p "'you're just part of the problem after all... Milo, I just don't think I can do it. I need some time'"
            show milo upset
            hide milo upset
            show milotalking
            m "'you're serious? That's all it takes?'"
            hide milotalking
            show miloupset
            p "her shift in character frightened me"
            p "'why are you so upset?'"
            hide miloupset
            show milotalking
            
            m "'What does it matter if I'm upset? You're leaving anyway. Without me, you have nothing. I thought I meant more than that.'"
            hide milotalking
            show miloneutral
            scene neutral with fade
            p "Nothing..."
            p "Fear shot through my nerves"
            p "I'm...sorry. No no, let's figure this out."
            p "We'll fix everything together, okay?"
            hide miloneutral
            show milosmiling
            hide milosmiling
            show milohappytalking
            m"'Okay.'"
            hide milohappytalking
            show milobigsmile

            return


