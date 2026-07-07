# Hyperlink audit — Version B

Source: `form_Ren副本(1).docx`

## Profile / contact links
- Email → `mailto:gqren@zju.edu.cn`
- LinkedIn → profile URL from the form
- X → profile URL from the form
- Google Scholar → full profile URL from the form

## Biography hyperlinks (10/10)
1. Zhang Lab
2. Robotics Institute
3. Carnegie Mellon University
4. Ji Zhang
5. ZJU-UIUC Institute,
6. Zhejiang University
7. K.C. Ting
8. Liangjing Yang
9. Distributed Autonomous Systems Laborator (DASLAB)
10. Girish Chowdhary

## News hyperlinks (2 logical targets)
- William Zhi
- Guest Lecture Series@ZJUI.

## Publication hyperlinks (14/14 logical links)
Each of the 7 publications has:
- title hyperlink → exact title target from the DOCX
- [Paper] hyperlink → exact paper target from the DOCX

### Source-DOCX anomaly normalized
The TRACE `[Paper]` text is split across two hyperlinks in the DOCX: `[` accidentally points to the TriPilot arXiv page, while `Paper]` points to the TRACE arXiv page. The website normalizes the full `[Paper]` label to the intended TRACE arXiv URL (`https://arxiv.org/abs/2606.14551`).

The source also stores the final period after `Guest Lecture Series@ZJUI` as a duplicate hyperlink to the same target. The website keeps the period inside the same visible hyperlink.
