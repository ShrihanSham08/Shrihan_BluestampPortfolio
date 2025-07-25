# Voice Assistant AI

<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->


# Project Description 

This project is a custom voice-activated AI assistant that allows users to interact naturally using spoken language. Built using Python and integrated with OpenAI's language model, the assistant can listen to your voice, and then respond to your command. The only problem is that it is not a real time OpenAI model, but I will later add an OpenAI model which has realtime data. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Shrihan.S | Milpitas High School | Electrical Engineering | Rising  Senior

![ShrihanS](https://github.com/user-attachments/assets/a01f44c9-3ed2-4998-9564-954f9755140c)


# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/c0KTvO1GWoM?si=LVuXH_n2H2aaIuBm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary 

My third and final milestone was completing the code for my custom OpenAI model. With this, I can now have real-time conversations with it—asking questions, giving commands, and getting spoken responses. The model is voice-activated and only responds after hearing the wake phrase, “Hey Jarvis,” to which it replies with a simple “Yes.” From there, I can issue any command I need. One limitation, however, is that the model’s knowledge was last updated in September 2023, so it may not be aware of more recent events or developments. The OpenAI talks back to me through a USB mic and a USB speaker which I connected to the Pi. 

## Challenges Faced 

The third milestone was by far the most challenging for me, as coding isn’t exactly my strongest skill. I ran into several issues along the way, but with the guidance and support of my instructor, I was eventually able to complete the code. We used Python to build the project, and one of the most valuable things I learned was how to use tools that highlight errors in my code, which made it much easier to identify and fix mistakes. Despite the difficulties, I really enjoyed the process of building my project—and now, I have my own OpenAI model that can respond and talk back to me.


# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/7tOhThaIJ6U?si=lUVrH5sd9osV27k6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Summary 

My second milestone was focused on installing the OpenAI software onto my Raspberry Pi to begin building a functional AI voice assistant. This task required more than just basic installation — I first had to research and identify a suitable ChatGPT model that could handle both audio input and output while also supporting text-based interaction. Since I was working on limited hardware, I needed a model that was lightweight enough to run efficiently on the Raspberry Pi, but still powerful enough to process and generate meaningful responses. I eventually chose to use OpenAI’s GPT-4o mini realtime via the API, which allowed me to send text queries and receive smart, conversational replies from the cloud. 

## Challenges Faced 

One of the most challenging parts of this milestone was finding the right AI model that would work well with the Raspberry Pi. Since the Pi has limited processing power and memory compared to a full computer, I knew I couldn’t run large language models like GPT-4.1 or the other ones directly on the device. I had to find a solution that would allow the Raspberry Pi to interact with an AI model through the cloud while still supporting both voice input/output and text-based communication. This led me to research OpenAI's available models, especially GPT-4o mini realtime, which offered a good balance between performance and speed, and could be accessed via API rather than being installed locally.



# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/03rZ_WAQo5A?si=KWCqZNXD3hb3f2-i" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Summary 

For my milestone, I focused on setting up the Raspberry Pi software and configuring all the necessary code on my computer to enable smooth communication between my development environment and the Pi. This part of the process involved installing the Raspberry Pi OS, connecting various peripherals, and preparing the system for Python-based development. I took time to carefully go through the setup guides, verified my connections, and ensured my Pi was properly powered and networked. Once the base system was running, I moved on to writing and uploading code that would allow for real-time interaction, particularly using OpenAI and audio input/output support.

## Challenges

 One of the most difficult moments came when the Raspberry Pi suddenly froze after I uploaded a new script. At first, I thought it was a minor glitch, but it turned out that the code had triggered a crash severe enough to require a full system reset. I had to re-flash the SD card, reinstall the OS, and reconfigure all of my previous settings—a process that costed me a lot of time.  

# Starter Project


<iframe width="560" height="315" src="https://www.youtube.com/embed/IN1WV0kRXRE?si=jzAv8u1_5rz0-BP7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


 

## Summary:
My starter project is a mini arcade system featuring classic games like Tetris, Snake, Car Racing, Space Invaders, and a Slot Machine. The system is controlled using seven buttons: up, down, left, right, start, pause/quit, and power/shoot/speed. Building the Retro Console was very fun. I learned a lot of new things like soldering. I had never done soldering before so building the retro console improved my soldering skills. I had to be very careful with the amount of solder I used, cause if I used too  much, my console would not work. 


## How the Components work together:
 For this project, I used two LED  displays, a 7-segment display, a buzzer, seven buttons, a capacitor, a battery holder with three AAA batteries, four transparent acrylic panels for the casing, an integrated circuit/microprocessor, and a custom PCB. The microprocessor is a compact but powerful component that processes input from the seven buttons and controls output to both the LED  screen and the 7-segment display.

## Challenges Faced:
  While building the retro gaming console, but the most difficult part for me was attaching and soldering the wires on the back of the board. The instructions provided were not very clear, especially when it came to the wiring diagram and the order in which the connections needed to be made. I struggled to understand where each wire was supposed to go, and at one point, I wasn't sure if I was damaging the board or just missing a step. The soldering itself was also tricky because the connections were small and required a steady hand, which made it even harder for me.





| **Started Project Parts** | **What these Parts are used for** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Main PCB	 | 	Houses all circuitry and the microcontroller; foundation of the console	 | $4.00|  <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a>|
| STC15 Microcontroller |	The brain of the console—runs the game logic | $1.50-$2.00 | <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
| 16×8 LED Matrix Display |Visual display for gameplay | $2.50-$4.00 | <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
| Tactile Buttons (6) |User inputs (game controls) | $1.00 | <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
| USB Type-C Port |Power input port | $1.50 | <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
| Resistors |Limit current to LEDs and other components | $0.10 | <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
| Capacitors |Stabilize power supply, filter noise	 | $0.20| <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
|Diodes |Ensure current flows correctly; protect from reverse voltage	 | $0.20| <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
|Crystal Oscillator	 |Provides clock signal for the microcontroller		 | $0.50| <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
|Pin Headers	 |Interfaces between PCB and external modules		 | $0.30| <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
|Acrylic Case	 | Protects the board and makes the console portable		 | $3.00-$5.00| <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |
|Wires / Connectors	 |For internal connections, power, button input	 | $0.50| <a href="https://www.amazon.com/Electronic-Console-Soldering-Practice-Educational/dp/B0DSSZ95K5?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A1L3U1U7SXO8E0&gQT=1"> Link </a> |





# Schematics 
Add a picture for now. 

# Code

    import speech_recognition as sr
    import pyttsx3
    import openai




    openai.api_key = "YOUR_OWN_API_KEY"

    recognizer = sr.Recognizer()
    tts = pyttsx3.init()
 
    WAKE_WORD = "hey jarvis"

    def speak(text):
     print(f"GPT: {text}")
    tts.say(text)
    tts.runAndWait()

    def listen_for_wake_word():
    with sr.Microphone() as source:
        print("🎧 Waiting for wake word...")
        recognizer.adjust_for_ambient_noise(source)
        audio = recognizer.listen(source)
        try:
            phrase = recognizer.recognize_google(audio).lower()
            print(f"You said: {phrase}")
            return WAKE_WORD in phrase
        except sr.UnknownValueError:
            return False
        except sr.RequestError:
            print("API unavailable")
            return False

    def listen_for_command():
    with sr.Microphone() as source:
        print("🎙️ Listening for your command...")
        recognizer.adjust_for_ambient_noise(source)
        audio = recognizer.listen(source)
        try:
            return recognizer.recognize_google(audio)
        except sr.UnknownValueError:
            return "Sorry, I didn't catch that."
        except sr.RequestError:
            return "Speech service is unavailable."

    def chat_with_gpt(prompt):
    response = openai.chat.completions.create(
        model="gpt-4o", 
        messages=[
            {"role": "system", "content": "You are a helpful assistant."},
            {"role": "user", "content": prompt}
        ]
    )
    return response.choices[0].message.content


    while True:
    if listen_for_wake_word():
        speak("Yes?")
        command = listen_for_command()
        print(f"You: {command}")
        # if command.lower() in ["stop", "exit", "quit"]:
        #     speak("Goodbye.")
        #     break
        gpt_response = chat_with_gpt(command)
        print("after response")
        speak(gpt_response)    


# Bill of Materials

| **Intensive Project Parts** | **What these Parts are used for** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| CanaKit Raspberry Pi 4 4GB Starter PRO Kit - 4GB RAM		 | Raspberry Pi, where you code the project	 | $139.99|  <a href="https://www.amazon.com/CanaKit-Raspberry-4GB-Starter-Kit/dp/B07V5JTMV9/ref=asc_df_B07V5JTMV9/?tag=hyprod-20&linkCode=df0&hvadid=693338329849&hvpos=&hvnetw=g&hvrand=18331739921598768352&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9061320&hvtargid=pla-1004184582672&mcid=9824999e31ae349e88b65c860ad01ca1&gad_source=1&th=1"> Link </a>|
| Amazon Basics USB Wired Computer Keyboard (QWERTY) and Mouse Bundle Pack |	Needed to control the mouse and type on the Raspberry Pi | $13.95 | <a href="https://www.amazon.com/AmazonBasics-Wired-Computer-Keyboard-Bundle/dp/B00B7GV802/ref=sr_1_1_ffob_sspa?crid=1VBS7R2GLGITW&dib=eyJ2IjoiMSJ9.CXiy0MSQ7oS5ab2-gtRxP59PzmhFj4Gk2geQcL2k-xsJKARBOvaecQvXxZzJdH7tv3zFyppS3afrjm0zMBbvnb5AvHreDWEmQqdrPvseDQ1K7amLQCOlYBD6Eb2rPel58kmonSddG5kIswe65AMKCBzitO2XKeaRWRund6dOj3qZpwDH2wYgaVgNz_Jnu51IjFkyvMALxU5CNdl9lcR6itK2EcpDO9xCTGBpmbW3B7gSTsSrZuqUZ4bWLBAeu5ETHrTXijmi6nXHlvMUJy988IjnYbbVzTFENG_srxqfPmQ.XmzDvKwWZpk7mSooFlq-iO8sYBf7a4lgpI_7fTKB2f4&dib_tag=se&keywords=usb%2Bmouse%2Band%2Bkeyboard&qid=1718294893&s=electronics&sprefix=usb%2Bmouse%2Band%2Bk%2Celectronics%2C140&sr=1-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| Mini Microphone	 | For the voice assistant to be able to hear you.	| $9.00 | <a href="https://www.amazon.com/KISEER-Microphone-Desktop-Recording-YouTube/dp/B071WH7FC6/ref=sr_1_49?dib=eyJ2IjoiMSJ9._duKGXX14Ei2lsMzDs9t2vyk8gfuyLieEl4NkKK46-uvCV_QCgGwsI3t_oorCwJJQM-bZ6BkIq7UbTLXTsxwSClw8156bRA2CaKjuzEq7M1YerNABcZys98j6JJvMbaPnIqL1-Kjn4PQz970f-FJAwTRd1WWX_pWf269K76tmhSjyFUwhFmcKzo60F4uYJaDvgPcqOsuuDD0QvpBZLIbaWLsttrBeutpVBzXpHHjJDFSmp20m6g1OK7spsV5W2Rm8DnRCtCxUI4E4xL3smQUgPSkAKL3IcI2pIznKla3348.t-Dl5tDpwxiAD9QqMbquG7WwwBjglLbtCvHYrOyOSb0&dib_tag=se&hvadid=557253842145&hvdev=c&hvlocphy=9032183&hvnetw=g&hvqmt=e&hvrand=2182861228486574729&hvtargid=kwd-355566415824&hydadcr=15453_13495278&keywords=mini+microphone+amazon&qid=1718321793&sr=8-49"> Link </a> |
| USB Mini Speaker	 |For the voice assistant be able to speak to you.	 | $12.99 | <a href="https://www.amazon.com/HONKYOB-Speaker-Computer-Multimedia-Notebook/dp/B075M7FHM1/ref=sr_1_2_sspa?crid=FR7PI8IPJB56&dib=eyJ2IjoiMSJ9.3NQlfBzyo_1KnxlkdUQcTTLGXSh49VhdM4wLdyEtkTvuiQ9KQ8zsv5qVSEnWGFYDSNS-48pUlbZzJ1DapVApIh2lnxaEUECErGLnquRElXL-64yjtEKoMriKRRuEae0qkVKVEmLGgkPvbbpU9RB3XabVru6LzeRfXrcllOBmobmvyxHsVFBVogPaC0Fd_uyCn5bV-CWvwVaaJUL4ADBjyLyiqReq6TEdq7GPXfLOiME.AeaC7Nyowuex2bsSTYI5Z08X7TqiLE9eqBZYI3ws3sk&dib_tag=se&keywords=mini%2Busb%2Bspeaker&qid=1718321989&sprefix=mini%2Busb%2Bspeaker%2Caps%2C144&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |

# Other Resources/Examples
Google
PiMyLifeUp
Chatgpt
Nazar Khan

