# css_sprite


1. ffmpeg으로 frame을 image로 추출
ex> ffmpeg -t 0:05 -i bmw5.mp4 -r 10 image-%04d.jpeg

2. ImageMagick을 이용해 이미지를 아래쪽으로 붙임
ex> convert image-*.jpeg -append sprite.jpg

https://blog.embed.ly/building-animated-covers-for-video-with-sprites-d260c445eb10

위 블로그 sample 코드 참고해 만듬

결과물 보기 
- https://blog.embed.ly/building-animated-covers-for-video-with-sprites-d260c445eb10
