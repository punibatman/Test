PASS 1 LOG
HandBrake 1.5.1 (2022011000)
OS: Microsoft Windows NT 10.0.19042.0
CPU: Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz
Ram: 32710 MB, 
GPU Information:
  NVIDIA GeForce RTX 2080 - 30.0.15.1109
  Citrix Indirect Display Adapter - 12.40.44.247
Screen: 2560x1440
Temp Dir: C:\Users\***\AppData\Local\Temp\
Install Dir: C:\Program Files\HandBrake\
Data Dir: C:\Users\***\AppData\Roaming\HandBrake

-------------------------------------------

 # Starting Encode ...

[22:50:34] base preset: Super HQ 1080p30 Surround (Modified)
[22:50:34] Remote Process started with Process ID: 8612 using port: 8037. Max Allowed Instances: 1
[22:50:34] Worker: Starting HandBrake Engine ...
[22:50:34] Worker: Starting Web Server on port 8037 ...
[22:50:34] Worker: Disconnected worker monitoring enabled!
[22:50:34] Compile-time hardening features are enabled
[22:50:34] hb_init: starting libhb thread
[22:50:34] Starting work at: Sun Jan 23 22:50:34 2022
[22:50:34] 1 job(s) to process
[22:50:34] json job:
{
  "Audio": {
    "AudioList": [
      {
        "Bitrate": 160,
        "DRC": 0,
        "Encoder": "av_aac",
        "Gain": 0,
        "Mixdown": 4,
        "NormalizeMixLevel": false,
        "Samplerate": 0,
        "Track": 0,
        "DitherMethod": 0
      },
      {
        "DRC": 0,
        "Encoder": "copy:ac3",
        "Gain": 0,
        "Mixdown": -1,
        "NormalizeMixLevel": false,
        "Samplerate": 0,
        "Track": 0,
        "DitherMethod": 0
      }
    ],
    "CopyMask": [
      "copy:aac",
      "copy:ac3",
      "copy:dtshd",
      "copy:dts",
      "copy:eac3",
      "copy:flac",
      "copy:mp3",
      "copy:truehd",
      "copy:mp2"
    ],
    "FallbackEncoder": "ac3"
  },
  "Destination": {
    "ChapterList": [
      {
        "Name": "Chapter 1"
      },
      {
        "Name": "Chapter 2"
      },
      {
        "Name": "Chapter 3"
      },
      {
        "Name": "Chapter 4"
      },
      {
        "Name": "Chapter 5"
      },
      {
        "Name": "Chapter 6"
      },
      {
        "Name": "Chapter 7"
      },
      {
        "Name": "Chapter 8"
      },
      {
        "Name": "Chapter 9"
      },
      {
        "Name": "Chapter 10"
      },
      {
        "Name": "Chapter 11"
      },
      {
        "Name": "Chapter 12"
      },
      {
        "Name": "Chapter 13"
      },
      {
        "Name": "Chapter 14"
      },
      {
        "Name": "Chapter 15"
      },
      {
        "Name": "Chapter 16"
      },
      {
        "Name": "Chapter 17"
      },
      {
        "Name": "Chapter 18"
      },
      {
        "Name": "Chapter 19"
      },
      {
        "Name": "Chapter 20"
      },
      {
        "Name": "Chapter 21"
      }
    ],
    "ChapterMarkers": true,
    "AlignAVStart": true,
    "File": "C:\\Users\\***\\Videos\\TESTA.m4v",
    "Mp4Options": {
      "IpodAtom": false,
      "Mp4Optimize": false
    },
    "Mux": "av_mp4"
  },
  "Filters": {
    "FilterList": [
      {
        "ID": 4,
        "Settings": {
          "mode": "7"
        }
      },
      {
        "ID": 3,
        "Settings": {
          "block-height": "16",
          "block-thresh": "40",
          "block-width": "16",
          "filter-mode": "2",
          "mode": "3",
          "motion-thresh": "1",
          "spatial-metric": "2",
          "spatial-thresh": "1"
        }
      },
      {
        "ID": 13,
        "Settings": {
          "crop-bottom": "0",
          "crop-left": "16",
          "crop-right": "6",
          "crop-top": "0",
          "height": "480",
          "width": "698"
        }
      },
      {
        "ID": 6,
        "Settings": {
          "mode": "0"
        }
      }
    ]
  },
  "PAR": {
    "Num": 8,
    "Den": 9
  },
  "Metadata": {},
  "SequenceID": 0,
  "Source": {
    "Angle": 1,
    "Range": {
      "Type": "chapter",
      "Start": 2,
      "End": 2
    },
    "Title": 1,
    "Path": "G:\\"
  },
  "Subtitle": {
    "Search": {
      "Burn": true,
      "Default": false,
      "Enable": true,
      "Forced": true
    },
    "SubtitleList": []
  },
  "Video": {
    "Encoder": "x265",
    "Level": "auto",
    "TwoPass": false,
    "Turbo": false,
    "ColorMatrixCode": 0,
    "Options": "",
    "Preset": "fast",
    "Profile": "auto",
    "Quality": 10,
    "QSV": {
      "Decode": false
    }
  }
}
[22:50:34] CPU: Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz
[22:50:34]  - Intel microarchitecture Kaby Lake
[22:50:34]  - logical processor count: 12
[22:50:34] Intel Quick Sync Video support: no
[22:50:34] hb_scan: path=G:\, title_index=1
src/libbluray/disc/disc.c:437: error opening file BDMV\index.bdmv
src/libbluray/disc/disc.c:437: error opening file BDMV\BACKUP\index.bdmv
src/libbluray/bluray.c:2646: nav_get_title_list(G:\) failed
[22:50:34] bd: not a bd - trying as a stream/file instead
libdvdnlibdvdnav: Unable to open device file G:\.
av: vm: dvd_read_name failed
libdvdnav: DVD disk reports itself with Region mask 0x00fe0000. Regions: 01
libdvdread: Attempting to retrieve all CSS keys
libdvdread: This can take a _long_ time, please be patient
libdvdread: Get key for /VIDEO_TS/VIDEO_TS.VOB at 0x0000011e
libdvdread: Elapsed time 0
libdvdread: Get key for /VIDEO_TS/VTS_01_0.VOB at 0x00001120
libdvdread: Elapsed time 0
libdvdread: Get key for /VIDEO_TS/VTS_01_1.VOB at 0x00001872
libdvdread: Elapsed time 0
libdvdread: Found 1 VTS's
libdvdread: Elapsed time 0
[22:50:35] scan: DVD has 2 title(s)
[22:50:35] scan: scanning title 1
[22:50:35] scan: duration is 01:33:13 (5593834 ms)
[22:50:35] pgc_id: 1, pgn: 1: pgc: 000001bf8019c9b0
[22:50:35] scan: checking audio 1
[22:50:35] scan: id=0x80bd, lang=English (AC3), 3cc=eng ext=1
[22:50:35] scan: title 1 has 21 chapters
[22:50:35] scan: chap 1, 158800 ms
[22:50:35] scan: chap 2, 196834 ms
[22:50:35] scan: chap 3, 210133 ms
[22:50:35] scan: chap 4, 356934 ms
[22:50:35] scan: chap 5, 327500 ms
[22:50:35] scan: chap 6, 328033 ms
[22:50:35] scan: chap 7, 260900 ms
[22:50:35] scan: chap 8, 280734 ms
[22:50:35] scan: chap 9, 292900 ms
[22:50:35] scan: chap 10, 383700 ms
[22:50:35] scan: chap 11, 322066 ms
[22:50:35] scan: chap 12, 325667 ms
[22:50:35] scan: chap 13, 398300 ms
[22:50:35] scan: chap 14, 232000 ms
[22:50:35] scan: chap 15, 309800 ms
[22:50:35] scan: chap 16, 243867 ms
[22:50:35] scan: chap 17, 177300 ms
[22:50:35] scan: chap 18, 361033 ms
[22:50:35] scan: chap 19, 335700 ms
[22:50:35] scan: chap 20, 83633 ms
[22:50:35] scan: chap 21, 8000 ms
[22:50:35] scan: aspect = 4:3
[22:50:35] scan: decoding previews for title 1
libdvdnav: DVD disk reports itself with Region mask 0x00fe0000. Regions: 01
[22:50:35] scan: title angle(s) 1
[22:50:35] scan: audio 0x80bd: ac3, rate=48000Hz, bitrate=192000 English (AC3) (2.0 ch) (192 kbps)
[22:50:37] scan: 10 previews, 720x480, 23.976 fps, autocrop = 0/0/16/6, aspect 4:3, PAR 8:9, color profile: 6-1-6, chroma location: left
[22:50:37] libhb: scan thread found 1 valid title(s)
[22:50:37] Skipping subtitle scan.  No suitable subtitle tracks.
[22:50:37] Starting Task: Encoding Pass
[22:50:37] Skipping vfr filter
[22:50:37] work: track 1, dithering not supported by codec
[22:50:37] work: only 1 chapter, disabling chapter markers
[22:50:37] job configuration:
[22:50:37]  * source
[22:50:37]    + G:\
[22:50:37]    + title 1, chapter(s) 2 to 2
[22:50:37]  * destination
[22:50:37]    + C:\Users\***\Videos\TESTA.m4v
[22:50:37]    + container: MPEG-4 (libavformat)
[22:50:37]      + align initial A/V stream timestamps
[22:50:37]  * video track
[22:50:37]    + decoder: mpeg2video 8-bit (yuv420p)
[22:50:37]      + bitrate 200 kbps
[22:50:37]    + filters
[22:50:37]      + Comb Detect (mode=3:spatial-metric=2:motion-thresh=1:spatial-thresh=1:filter-mode=2:block-thresh=40:block-width=16:block-height=16)
[22:50:37]      + Decomb (mode=39)
[22:50:37]      + Crop and Scale (width=698:height=480:crop-top=0:crop-bottom=0:crop-left=16:crop-right=6)
[22:50:37]        + source: 720 * 480, crop (0/0/16/6): 698 * 480, scale: 698 * 480
[22:50:37]    + Output geometry
[22:50:37]      + storage dimensions: 698 x 480
[22:50:37]      + pixel aspect ratio: 8 : 9
[22:50:37]      + display dimensions: 620 x 480
[22:50:37]    + encoder: H.265 (libx265)
[22:50:37]      + preset:  fast
[22:50:37]      + profile: auto
[22:50:37]      + level:   auto
[22:50:37]      + quality: 10.00 (RF)
[22:50:37]      + color profile: 6-1-6
[22:50:37]      + chroma location: left
[22:50:37]  * audio track 1
[22:50:37]    + decoder: English (AC3) (2.0 ch) (192 kbps) (track 1, id 0x80bd)
[22:50:37]      + bitrate: 192 kbps, samplerate: 48000 Hz
[22:50:37]    + mixdown: Stereo
[22:50:37]    + encoder: AAC (libavcodec)
[22:50:37]      + bitrate: 160 kbps, samplerate: 48000 Hz
[22:50:37]  * audio track 2
[22:50:37]    + decoder: English (AC3) (2.0 ch) (192 kbps) (track 1, id 0x80bd)
[22:50:37]      + bitrate: 192 kbps, samplerate: 48000 Hz
[22:50:37]    + AC3 Passthru
libdvdlibdvdnav: Unable to open device file G:\.
nav: vm: dvd_read_name failed
libdvdnav: DVD disk reports itself with Region mask 0x00fe0000. Regions: 01
libdvdread: Attempting to retrieve all CSS keys
libdvdread: This can take a _long_ time, please be patient
libdvdread: Get key for /VIDEO_TS/VIDEO_TS.VOB at 0x0000011e
libdvdread: Elapsed time 0
libdvdread: Get key for /VIDEO_TS/VTS_01_0.VOB at 0x00001120
libdvdread: Elapsed time 0
libdvdread: Get key for /VIDEO_TS/VTS_01_1.VOB at 0x00001872
libdvdread: Elapsed time 0
libdvdread: Found 1 VTS's
libdvdread: Elapsed time 0
libdvdnav: DVD disk reports itself with Region mask 0x00fe0000. Regions: 01
[22:50:37] sync: expecting 4719 video frames
x265 [info]: HEVC encoder version 3.5+1-f0c1022b6
x265 [info]: build info [Windows][GCC 10.2.0][64 bit] 8bit+10bit+12bit
x265 [info]: using cpu capabilities: MMX2 SSE2Fast LZCNT SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2
x265 [info]: Main profile, Level-3 (Main tier)
x265 [info]: Thread pool created using 12 threads
x265 [info]: Slices                              : 1
x265 [info]: frame threads / pool features       : 3 / wpp(8 rows)
x265 [warning]: Source height < 720p; disabling lookahead-slices
x265 [info]: Coding QT: max CU size, min CU size : 64 / 8
x265 [info]: Residual QT: max TU size, max depth : 32 / 1 inter / 1 intra
x265 [info]: ME / range / subpel / merge         : hex / 57 / 2 / 2
x265 [info]: Keyframe min / max / scenecut / bias  : 24 / 240 / 40 / 5.00
x265 [info]: Lookahead / bframes / badapt        : 15 / 4 / 0
x265 [info]: b-pyramid / weightp / weightb       : 1 / 1 / 0
x265 [info]: References / ref-limit  cu / depth  : 3 / on / on
x265 [info]: AQ: mode / str / qg-size / cu-tree  : 2 / 1.0 / 32 / 1
x265 [info]: Rate Control / qCompress            : CRF-10.0 / 0.60
x265 [info]: tools: rd=2 psy-rd=2.00 rskip mode=1 signhide tmvp fast-intra
x265 [info]: tools: strong-intra-smoothing deblock sao
[22:50:38] sync: first pts video is 0
[22:50:38] sync: first pts audio 0x80bd is 0
[22:50:38] sync: first pts audio 0x80bd is 0
[22:50:38] sync: "Chapter 2" (2) at frame 6 time 18768
[22:50:43] 13.689667s: Film -> Video
[22:50:43] 13.756400s: Video -> Film
[22:50:46] 17.626934s: Film -> Video
[22:50:46] 17.660299s: Video -> Film
[22:50:59] 46.989590s: Film -> Video
[22:50:59] 47.056332s: Video -> Film
[22:51:03] 54.897488s: Film -> Video
[22:51:03] 54.971622s: Video -> Film
[22:51:29] 111.053596s: Film -> Video
[22:51:29] 111.086967s: Video -> Film
[22:52:07] reader: end of chapter 2 (media 2) reached at media chapter 3
[22:52:07] reader: done. 1 scr changes
[22:52:09] work: average encoding speed for job is 52.662388 fps
[22:52:09] comb detect: heavy 4008 | light 708 | uncombed 38 | total 4754
[22:52:09] decomb: deinterlaced 4008 | blended 708 | unfiltered 38 | total 4754
[22:52:09] ac3-decoder done: 6158 frames, 0 decoder errors
[22:52:09] ac3-decoder done: 6158 frames, 0 decoder errors
[22:52:09] mpeg2video-decoder done: 4749 frames, 0 decoder errors
[22:52:09] sync: got 4754 frames, 4719 expected
[22:52:09] sync: framerate min 23.976 fps, max 29.970 fps, avg 24.112 fps
[aac @ 000001bf801c3d40] Ignoring attempt to flush encoder that doesn't support it
[aac @ 000001bf801c3d40] Qavg: 169.812
x265 [info]: frame I:     39, Avg QP:9.98  kb/s: 20862.98
x265 [info]: frame P:    945, Avg QP:10.95  kb/s: 15531.93
x265 [info]: frame B:   3770, Avg QP:15.59  kb/s: 7032.78
x265 [info]: Weighted P-Frames: Y:8.5% UV:6.2%
x265 [info]: consecutive B-frames: 3.9% 0.0% 0.2% 1.0% 94.9%
encoded 4754 frames in 92.03s (51.66 fps), 8835.70 kb/s, Avg QP:14.62
[22:52:10] mux: track 0, 4754 frames, 219013307 bytes, 8885.06 kbps, fifo 512
[22:52:10] mux: track 1, 9238 frames, 3957419 bytes, 160.55 kbps, fifo 1024
[22:52:10] mux: track 2, 6158 frames, 4729344 bytes, 191.86 kbps, fifo 512
[22:52:10] Finished work at: Sun Jan 23 22:52:10 2022
[22:52:10] libhb: work result = 0

 # Job Completed!



