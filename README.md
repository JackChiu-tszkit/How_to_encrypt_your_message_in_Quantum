# How to encrypt your message and how to discover eavesdrop.
This is the first time I coded in Qiskit and uploaded in github. The code is based on the quantum key distribution in Qiskit document.
The project is about how to encrypt your message in qiskit through a public channel and how to discover probable eavesdrop. 
It is only for MVP or a short demonstration. 

## Scenairo
I made a scenairo where Jack would like to send a message to Rose through a public channel. Eve will be the eavesdrop to steal the message.
The message Jack sends will be encrypted in Quantum method and Rose will receive the encrypted message and decode through Quantum Measurement.
Encoding approach is simply to convert the binary data into a quantum circuit. Decoding approach is simply to measure the quantum circuit. 
The binary data is from converting the string (Message). 

## How to start
You can firstly register a user in Quantum Lab and start to use their built-in notebook. 
Upload the files I made in github and select to run all the cells. 
Write the message Jack wants to send to Rose.
Be caution that the message is only valid for a single string currently such as "Howareyou", "Whoareyou" and etc. 

## Work in Progress
There are still a lot of things I need to enhance for the code. It will be next release with enhancement soon. 
