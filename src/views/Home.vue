<template>
  <div class="overflow-x-hidden">
    <Header />
    <div class="background--alt">
      <div class="container mx-auto flex md:min-h-screen">
        <div class="flex">
          <div
            class="inline-flex flex-col md:flex-row flex-no-wrap md:items-center"
          >
            <div class="md:w-1/2 px-6 md:px-12 flex flex-col md:items-start">
              <h1
                class="mt-8 text-xl lg:text-6xl max-w-md gt-walsheim-medium leading-tight"
              >
                Sheltered
              </h1>
              <h2
                class="mt-8 text-xl lg:text-3xl max-w-md gt-walsheim-medium leading-tight"
              >
                Sheltered is a Secure & Private Video Call App.
              </h2>
              <div
                class="mt-4 text-base lg:text-lg max-w-md open-sans-regular leading-snug"
              >
                No authentication needed, only a username of choice and a
                randomly generated ID to connect users into a video call room. The ID can be encrypted/decrypted and safely exchanged through a secure encrypted chat system.
              </div>
              <transition appear name="fade">
                <div class="inline-flex flex-row">
                  <a
                    class="mt-8 grow--button background text-center pt-3 pb-3 px-3 border-4 border-black rounded-lg gt-walsheim-medium"
                    href="https://sheltered.netlify.app/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    Sheltered Video Call
                  </a>
                  <a
                    class="mt-8 ml-8 grow--button background text-center pt-3 pb-3 px-3 border-4 border-black rounded-lg gt-walsheim-medium"
                    href="https://sheltered-chat.netlify.app/"
                    target="_blank"
                    rel="noopener noreferrer"
                  >
                    Sheltered Chat
                  </a>
                </div>
              </transition>
            </div>
            <div class="md:w-1/2 md:px-4 hidden md:block">
              <transition appear name="fade">
                <img
                  class="hidden md:block w-96 rounded-lg w-72 border-black border-4"
                  src="@/assets/img/intro/sheltered-mockup-pc.jpg"
                />
              </transition>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="features" class="flex px-10 md:px-0 background--alt">
      <div class="container mx-auto flex flex-col flex-no-wrap items-center mt-24 mb-24 md:mb-32">
        <h1
          class="text-2xl md:text-4xl text-center gt-walsheim-medium leading-tight"
        >
          Introducing the Sheltered Video Call System:
        </h1>
        <p
          class="mt-8 text-center text-base md:text-xl lg:text-xl open-sans-regular leading-snug md:max-w-6xl md:px-16 md:py-16 border-8 border-black rounded-md background"
        >
          📲 User1 enters Sheltered. Types a random Username and clicks on 'Copy
          ID' with is the randomly generated call ID. 
          <br></br>
          📤 User2 sends User1 his/her public key in order for User1 to encrypt the call ID with it <br></br>
          🔑 User1 clicks 'Generate
          Public Key/Private Key' and then pastes User2 Public Key on the Public Key field and the random call ID into the
          RSA Encryption field and encrypts it. <br></br> 
          📤 User1 sends User2 the encrypted
          call ID <br></br>
          📥 User2 ,after receiving the
          above, types a random Username and pastes the
          encrypted ID into its respective field and decrypts it with his/her private key <br></br>
          🔐 User2 decrypts the encrypted call ID. User2 pastes the now
          decrypted call into the 'Call ID' field and calls User1.<br></br> 
          📞 User1 sees
          User2 calling and picks up. They are now safely in a private and
          encrypted video call!
        </p>
      </div>
    </div>
    <div class="flex px-10 md:px-0 background--alt">
      <div
        class="container mx-auto flex flex-col items-center mt-24 mb-24 md:mb-32"
      >
        <h1 class="text-2xl md:text-4xl gt-walsheim-medium leading-tight">
          Introducing the Sheltered Chat System:
        </h1>
        <p
          class="mt-8 text-center text-base md:text-xl lg:text-xl open-sans-regular leading-snug md:max-w-6xl md:px-8 md:py-16 border-8 border-black rounded-md background"
        >
          🤝 User1 contacts User2 (via a third-party app or IRL) and they schedule the date and time they will join their Private Chat Room. They have to decide the unique name of their private chat room.
          <br></br>
          📲 They both have to enter a nickname and type the same Chat Room Name in the Chat System login screen. <br></br> 
          💭 They are now connected in the same Private Chat Room and their messages are completely encrypted. <br></br>
          🔑 They can exchange their Encrypted Video Call IDs and their Public Encryption Keys in order to decrypt the video call ID later on the Sheltered Video Call platform. <br></br>
        </p>
        <div class="flex flex-col items-center">
          <div
            class="mt-16 md:mt-32 flex flex-col-reverse md:flex-row items-center"
          >
            <div
              class="flex flex-col items-center md:items-start max-w-sm px-4 md:px-0 text-center md:text-left md:pr-12"
            >
              <h2
                class="mt-8 md:mt-0 text-xl md:text-2xl md:px-4 header-color gt-walsheim-medium"
              >
                Technologies used
              </h2>
              <p class="mt-2 text-base md:text-lg md:px-4 open-sans-regular">
                “Sheltered” was developed using state-of-the art web
                technologies including JavaScript, HTML5, and CSS and frameworks like
                NodeJS, React and ExpressJS as well as the Ionic framework (Capacitor) which, by
                wrapping native code into a JavaScript API, produces a corresponding
                mobile app to be distributed via Play Store and App Store.
              </p>
            </div>
            <div class="w-3/4 md:w-48 lg:w-64 background--illustration border-8 border-black rounded-md">
              <img
                src="@/assets/img/illustrations/video_call_illustration.png"
                alt=""
              />
            </div>
          </div>
          <div
            class="mt-16 md:mt-32 flex flex-col-reverse md:flex-row items-center"
          >
            <div
              class="flex flex-col items-center md:items-start  max-w-sm px-4 md:px-0 text-center md:text-left md:pr-12"
            >
              <h2
                class="mt-8 md:mt-0 text-xl md:text-2xl md:px-4 header-color gt-walsheim-medium"
              >
                Our purpose
              </h2>
              <p class="mt-2 text-base md:text-lg md:px-4 open-sans-regular">
                We present “Sheltered”, a hybrid application which allows pairs of
                users to securely and privately set-up and make video calls over the
                internet. No registration or authorization is required.
              </p>
            </div>
            <div class="w-3/4 md:w-48 lg:w-64 background--illustration border-8 border-black rounded-md">
              <img src="@/assets/img/illustrations/video_call_illustration1.png" alt="" />
            </div>
          </div>
          <div
            class="mt-16 md:mt-32 flex flex-col-reverse md:flex-row items-center"
          >
            <div
              class="flex flex-col items-center md:items-start  max-w-sm px-4 md:px-0 text-center md:text-left md:pr-12"
            >
              <h2
                class="mt-8 md:mt-0 text-xl md:text-2xl md:px-4 header-color gt-walsheim-medium"
              >
                Ways of usage
              </h2>
              <p class="mt-2 text-base md:text-lg md:px-2 open-sans-regular">
                In critical real-world scenaria including
                confidential online business meetings, lawyer-client discussions,
                teleconferences with accountants for the analysis of confidential
                financial data, doctor-patient online meeting on issues requiring
                medical confidentiality, meetings of government members on critical
                political or national issues, or just for users who simply wish to be able to perform
                secure and private video calls over IP avoiding registration and risk
                of interception.
              </p>
            </div>
            <div class="w-3/4 md:w-48 lg:w-64 lg:w-6 background--illustration border-8 border-black rounded-md">
              <img
                src="@/assets/img/illustrations/video_call_illustration2.png"
                alt=""
              />
            </div>
          </div>
          <div
            class="mt-16 md:mt-32 flex flex-col-reverse md:flex-row items-center"
          >
            <div
              class="flex flex-col items-center md:items-start  max-w-sm px-3 md:px-0 text-center md:text-left md:pr-12"
            >
              <h2
                class="mt-8 md:mt-0 text-xl md:text-2xl md:px-4 header-color gt-walsheim-medium"
              >
                Upcoming releases
              </h2>
              <p class="mt-2 text-base md:text-lg md:px-4 open-sans-regular">
                We constantly strive to ensure a more safe and secure online communication.
              </p>
            </div>
            <div class="w-3/4 md:w-48 lg:w-64 background--illustration border-8 border-black rounded-md">
              <img src="@/assets/img/illustrations/video_call_illustration3.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Footer
  }
};
</script>
