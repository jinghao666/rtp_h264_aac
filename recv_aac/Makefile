include_path=/home/chris/work/rtp-rtcp/lib/0502/include/jrtplib3
lib_path=/home/chris/work/rtp-rtcp/lib/0502/lib

ffmpeg_include_path=/home/chris/work/ffmpeg/refs/ffmpeg-1.2/include
ffmpeg_lib_path=/home/chris/work/ffmpeg/refs/ffmpeg-1.2/lib

all:
	#g++ 264_data_send.cpp -I${include_path} -L${lib_path} -ljrtp
	g++  -o test recv_audio_data.cpp -I${include_path} -L${lib_path}  -ljrtp 
  