PART 1:

1) Code for ChatServer:
<img width="1131" alt="Screenshot 2024-04-24 at 11 38 36 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/83d124a6-ddd7-4dba-8ae0-65f8882cea6d">

<img width="763" alt="Screenshot 2024-04-24 at 11 39 06 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/ef87de5b-69ea-459e-b469-ee23c5ecfe6d">

<img width="703" alt="Screenshot 2024-04-24 at 11 44 56 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/b5f626cc-09f8-4498-966a-1345c662d7d3">


2) Two screenshots and answers to three questions
<img width="588" alt="Screenshot 2024-04-24 at 11 41 10 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/037ac4e9-07f9-4bb0-863c-167fe287bb92">

  a) The method handleRequest from the ChatMessageHandler class is called.

  b)The method receives a URI representing the incoming request, containing parameters like s=Hello and user=Diego.

  c)In this specific request, the chatHistory field of the ChatMessageHandler class changes as follows: prior to the request, chatHistory is empty, and after processing the request /add-message?s=Hello&user=Diego, chatHistory contains the message `Diego: Hello\n`.
  
<img width="705" alt="Screenshot 2024-04-24 at 11 42 28 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/e65db08c-d648-4ef9-af09-3a89a8205c01">

  a)Methods called were handleRequest from ChatMessageHandler.

  b)Arguments were were URI represented with s=How is your day and user=Eduardo.

  c)In this specific request, the chatHistory field of the ChatMessageHandler class is updated as follows: before the request, chatHistory contains 'Diego: Hello'; after processing the request /add-message?s=How%20is%20your%20day?&user=Eduardo, chatHistory includes `Diego: Hello/n` and `Eduardo: How is your day?/n`.
  



PART 2:

1)On the command line of your computer, run ls with the absolute path to the private key for your SSH key for logging into ieng6.

<img width="530" alt="Screenshot 2024-04-24 at 10 44 28 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/594da9ec-5b47-43b1-9c33-c7da208a2fc5">


2)run ls with the absolute path to the public key for your SSH key for logging into ieng6 (this is the one you copied to your account on ieng6 using ssh-copy-id, so it should be a path on ieng6's file system).

<img width="723" alt="Screenshot 2024-05-08 at 11 56 40 AM" src="https://github.com/Diegoocse/CSE15L--LabReport2/assets/146890166/0281ac8c-8b31-4aed-9b34-7fef8f7305c7">



3) terminal interaction where you log into your ieng6 account without being asked for a password.

<img width="858" alt="Screenshot 2024-04-24 at 10 37 48 PM" src="https://github.com/Diegoocse/CSE15l-lab-report1/assets/146890166/7bf336f1-59c9-499a-921a-74320847679e">


PART 3:

During lab of week 2 one of the things that I learn was about curl and how it is a versatile command when it comes to downloading and uploading files. During lab of week 3 something that I learned was how to log into a remote server without the need of a password which saves me time for future use. These are some of the things I learned during labs that I didn't know before
