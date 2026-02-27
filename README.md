# BQ24074-Based-Charger
I wanted a lithium battery charging module, but I felt that simply buying one wouldn't be fun. So I decided to create my own module from scratch. First, I researched a bit about which chip would be best for me and decided to go with the BQ24074 for its simplicity and small size. I based it on the Texas Instruments datasheet to create it. I decided to set it to USB500 mode because if I set it to the 1.2A fast charge mode, it would get too hot and I feel like I would never use that.Here are some pictures of my schematic and my PCB:
<img width="1004" height="444" alt="Captura de pantalla 2026-02-25 004203" src="https://github.com/user-attachments/assets/bee3a399-461d-4d2f-8e3e-8a4fdacf66e6" />
<img width="313" height="589" alt="image" src="https://github.com/user-attachments/assets/f4fcacdc-d092-4389-adfa-1626842aa285" />
<img width="319" height="589" alt="image" src="https://github.com/user-attachments/assets/908d512d-bcef-4c6b-901f-b0d0ae8c269b" />
<img width="814" height="430" alt="fb0caab4e54b4cd78e72f23c9ea28f67_T" src="https://github.com/user-attachments/assets/4a5aac4d-b3bf-4fd2-970f-b701a448a5aa" />


My goal with this module was to make it as compact as possible. I wanted to make a PCB with components on both sides, but that would have increased the cost too much to have it made with JLCPB. I would like to solder it myself, but the problem is that to solder the chip I would need a heat gun or a hot plate, neither of which I have. So I ended up with this, which is the simplest option.
