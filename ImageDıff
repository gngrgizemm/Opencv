import cv2
#image
image1=cv2.imread("image0.jpg")
image2=cv2.imread("image1.jpg")
diff =cv2.absdiff(image1,image2)
-,diff = cv2.threashold(diff,32,0,cv2.THRESH_TOZERO)
-,diff = cv2.threashold(diff,0,255,cv2.THRESH_BINARY)

diff =cv2.medianBlur(diff,5)

#cam
cam=cv2.VİdeoCapture('video0.mp4')
cam2=cv2.VİdeoCapture('video0.mp4')

while(kamera.isOpened()):
    ret,goruntu =cam.read()
    gray1=cv2.cvtColor(goruntu,cv2.COLOR_BGR2GRAY)
    
    ret2,goruntu2 =cam2.read()
    gray1=cv2.cvtColor(goruntu,cv2.COLOR_BGR2GRAY)
    
    
    diff =cv2.absdiff(goruntu,goruntu2)
    
