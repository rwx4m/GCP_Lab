# GSP519_Command Design in Vertex AI_Challenge Lab
START LAB

1. Go to https://console.cloud.google.com/vertex-ai/studio/saved-prompts?project=
2. Import `Cymbal Product Analysis.json`
3. Go to point 1 and open new tab
4. Create prompt -> Freeform
5. change command name to `Cymbal Tagline Generator Template`
6. Model `gemini-1.5-pro`
7. Ouput format JSON
8. System Instruction:
   `Cymbal Direct is partnering with an outdoor gear retailer. They're launching a new line of products designed to encourage young people to explore the outdoors. Help them create catchy taglines for this product line.`
9. On Prompt, Add 2 Examples below:

| Input                                                                                                                                     | Output                                             |
|-------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| Write a tagline for a durable backpack designed for hikers that makes them feel prepared. Consider styles like minimalist.                 | Built for the Journey: Your Adventure Essentials.  |
| Write a tagline for an eco-friendly rain jacket designed for families that makes them feel connected. Consider styles like playful, with a touch of humor. | Explore More, Worry Less. Weather the fun together! |

10. Test Section:
    copy & paste `Write a tagline for a lightweight tent designed for seasoned explorers that makes them feel free. Consider styles like poetic.`
11. Click right arrow "=>"
12. Save Prompt
13. Vertex AI > Workbench.
14. Open JupyterLab
15. Create `image-analysis.ipynb` & `tagline-generator.ipynb` / Upload 2 files
16. Run tagline-generator first
17. Copy project id to image-analysis code then RUN

## END LAB

NOTE:
if task 1 fails, go back to point 1 and select `Cymbal Product Analysis`. Then RUN again.
Make sure points 6 & 7 have been implemented.
