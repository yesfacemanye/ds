# ds
yes
New auto clicker javascript:clicker:{"use strict";const{Number}=self;const milliseconds=Number.parseInt(self.prompt("How many seconds do you want to wait before clicking again?",'1'),10);if(false===Number.isSafeInteger(milliseconds)){self.alert("Input was not an integer");break clicker;}let clientX=0,clientY=0;const{document}=self;self.setInterval(()=>{document.elementFromPoint(clientX,clientY)?.click?.();},milliseconds);document.addEventListener("mousemove",event=>{({clientX,clientY}=event);},{passive:true});}
