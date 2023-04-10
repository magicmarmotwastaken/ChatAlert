# ChatAlert
Simple audible alert when your chatroom receives a message

Replace "USERNAME" at the top of the script to match your chatroom's URL.
`// @match        https://kick.com/USERNAME/chatroom`

You can use a different sound by converting any mp3 to Base64 @ https://base64.guru/converter/encode/audio/mp3 and replacing the string in the line in the script:

`        let alertSound = new Audio ("data:audio/mp3;base64,YOUR_AUDIO_STRING");`
