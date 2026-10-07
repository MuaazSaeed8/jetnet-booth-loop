# JETNET AI · Booth 3030 trade-show loop

The NBAA-BACE 2026 loop for the 65-inch booth display: 2 min 20 s, seamless, silent.

## What's here

| Path | What it is |
|---|---|
| `4K-master/` | **The file for the TV**, in 6 parts (GitHub caps single files at 100 MB). Join them once, as below. 3840 × 2160, 30 fps, H.264 High, Rec. 709, 533 MB. Set the player to repeat. |
| `4K-per-app/` | One 4K clip per app, 17 s each, each starting with its slot-machine spin. Ready to play as they are. |
| `JETNET_AI_Booth_Loop_1080p.mp4` | The full loop at 1920 × 1080 for laptops, web and review. Ready to play as it is. |

## Getting the 4K master

1. On this page click **Code → Download ZIP** and unzip it. Or download the six `.part` files from `4K-master/` into one folder.
2. Join the parts.

   **Mac:** open Terminal, type `cd ` (with a space), drag the `4K-master` folder into the window, press Return, then run:

   ```
   cat JETNET_AI_Booth_Loop_4K_master.mp4.part* > JETNET_AI_Booth_Loop_4K_master.mp4
   ```

   **Windows:** open Command Prompt in the `4K-master` folder and run:

   ```
   copy /b JETNET_AI_Booth_Loop_4K_master.mp4.part1+JETNET_AI_Booth_Loop_4K_master.mp4.part2+JETNET_AI_Booth_Loop_4K_master.mp4.part3+JETNET_AI_Booth_Loop_4K_master.mp4.part4+JETNET_AI_Booth_Loop_4K_master.mp4.part5+JETNET_AI_Booth_Loop_4K_master.mp4.part6 JETNET_AI_Booth_Loop_4K_master.mp4
   ```

3. Optional check: the joined file is 533,431,610 bytes and its SHA-256 is
   `0f079b5ff67c739c366090aa426ad9c741503586ebf81777550a53bf06981844`
   (Mac: `shasum -a 256 JETNET_AI_Booth_Loop_4K_master.mp4`).

## Notes

- Both QR codes open https://www.jetnet.com.
- All answer cards show fictional sample data and are labelled as such.
- The opener line "First in aviation" still needs legal sign-off before the show.
