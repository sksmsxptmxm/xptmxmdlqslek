## In-the-wild Audio to Image Synthesis with Optimizing Attentions on Text Representations
### Audio and Generated Images Download
You can download additional images and audio files.

Audio Files : 
[Audioset](https://drive.google.com/file/d/1WNwCf5Haivncpw9yrrKtColP-fIvLqC-/view?usp=sharing), 
[Multi ESC-50](https://drive.google.com/file/d/1MUoOQc_T4s3-IExRXFvd1qUifaBHieRi/view?usp=sharing), 
[Single ESC-50](https://drive.google.com/file/d/10GV53y9WDpFY4BPCygqpupffMriokX2d/view?usp=sharing)

Additionoal Generated Images : 

[Audioset (Our(OPT))](https://drive.google.com/file/d/11YNed-UDSqLJd9Y7DbeJxrGjtkTgU1jg/view?usp=share_link)
[Audioset(Baseline)](https://drive.google.com/file/d/1Q90UJfE3pYEIvW4GApPrI2cB2whz3VM1/view?usp=share_link)

[Multi-ESC50 (Our(OPT))](https://drive.google.com/file/d/1em_wNmufdMHu7MmRoGuOIgnYPD5GOURE/view?usp=share_link)
[Multi-ESC50 (Baseline)](https://drive.google.com/file/d/1ByR7J3eu4JioSp9-zEIDNOYjcSe1x754/view?usp=share_link)

[Single-ESC50 (Our(OPT))](https://drive.google.com/file/d/1Sz8-hAxtONORMITXgtcSNN-WONEVRp80/view?usp=share_link)
[Single-ESC50(Baseline)](https://drive.google.com/file/d/1PNjG9dww1F6AO5UFSrX4nN-gc48MyrYD/view?usp=share_link)

---


### Direct Sound Optimization Examples:
#### A : Ours(wo/Attentions), W Init vector (without Audio Attention and Setence Attention) + Direct Sound Optimization
#### B : Ours(w Attentions), W Init vector (with Audio Attention and Setence Attention) + Direct Sound Optimization
|Audio|A. Epoch : 0|A. Epoch : 5|A. Epoch : 10|B. Epoch : 0|B. Epoch : 5|B. Epoch : 10|
|---|------|---|---|------|---|---|
[Audio1](https://drive.google.com/file/d/1q_AMmkanTvqlB4CMwNn-Eyu17VdAWt4g/view?usp=share_link)|<img src="https://user-images.githubusercontent.com/124040029/215919411-43972d60-ea20-4908-80ca-c24714243916.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215919743-a4560c39-fe20-4d22-b41a-6d37ca251505.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215919752-dfcf354e-1924-4c17-8723-9cda2f836abf.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921118-35a94089-5c3d-4345-bdbd-1d0001cb8c4b.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921127-31e06417-b876-4918-bbac-077bfc29f52c.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921138-7e74ebcf-f092-4786-a98a-33d9f780bf67.png" width=100 height=100>|
|[Audio2](https://drive.google.com/file/d/1l4nB-e1T0QBIqDx1imXYd7P6pM8vBMDp/view?usp=sharing)|<img src="https://user-images.githubusercontent.com/124040029/215919968-f8b8b224-b0ea-49c7-9866-e821749098ce.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215919975-5f6191ea-1781-4e13-9122-f0de01567323.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215919983-e51f0e3f-7082-43ef-8915-fba7d96fe539.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921258-d680f059-0c9b-4bf7-be4f-12772f42244d.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921269-a22260b1-c1ea-4ea0-909d-768ba3896781.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921275-d4fa5dcd-089d-4056-a131-68972ab8e3fd.png" width=100 height=100>|
|[Audio3](https://drive.google.com/file/d/1kpqE-vET7OniyaWkhwCugGZ05hI6WCEU/view?usp=share_link)|<img src="https://user-images.githubusercontent.com/124040029/215920379-2610459b-7c1a-472c-8893-c029f2481029.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215920391-5329970c-e236-4cd8-b2a2-d08fb0bf1b75.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215920408-7aa37a25-d50c-4f5c-afc7-28a9b748874a.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921387-9e36ed74-57f4-4c7f-8e3a-05546b0f82da.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921403-8f9e35ae-e4fc-47e3-a02e-dc40e24130fc.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921414-622b348c-46b7-4751-aaca-28d7b5642283.png" width=100 height=100>|
|[Audio4](https://drive.google.com/file/d/12hYlliGNL4Yb04tbeYxHH5IMzu_9SYMh/view?usp=share_link)|<img src="https://user-images.githubusercontent.com/124040029/215920228-c41ac9d3-24c0-453a-b1da-84c86635a1ae.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215920237-7265b55a-26e1-430d-96eb-a080cc6b5656.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215920247-b777844c-cfec-432a-a504-7fb5bf55d75e.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921466-a0ea4272-ecfb-449f-9398-49e32dd3286b.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921474-6c8cf2dd-cabc-4884-a758-36f3ee136c45.png" width=100 height=100>|<img src="https://user-images.githubusercontent.com/124040029/215921480-670067e4-b4f2-4c73-a2fc-27a997ef9c9e.png" width=100 height=100>| 






