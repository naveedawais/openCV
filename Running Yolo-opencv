from ultralytics import YOLO
import cv2


model = YOLO('yolo-weights/yolov8n.pt')

results = model('media-files/videos/3.mp4', show=True)

cv2.waitKey(0)
