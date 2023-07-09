# Image-Caption-Generation-using-VGG19-and-Dense-LSTM

An encoder-decoder-based description generation. Existing papers used only objects
for descriptions, but the relationship between them is equally important. Which in turn requires
context information. For which technique like Long Short-Term Memory (LSTM) is required. This
paper proposes an encoder-decoder-based methodology to generate human-like textual descriptions.
Dense-LSTM is presented for better description as a decoder with modified VGG19 as an encoder
to capture information to describe the scene. Standard datasets Flickr8K and Flickr30k are used for
testing and training purposes. BLEU (Bilingual Evaluation Understudy) score is used to evaluate
a generated text.

VGG19 is used as an encoder with slight modification to
get the desired dimensions. A novel Dense-LSTM is proposed as a decoder for the textual
part.


Additionally, another approach has been suggested using ViT Base + GPT2_L model.

Here are the following links of report and PPT:-

https://docs.google.com/document/d/1KC35BhD_usZiRt6Okynyiw53U2OnsEEe-Nc2xlnglmo/edit?pli=1#heading=h.ajwnem8pvzkh

https://docs.google.com/presentation/d/1Ue2c5Xqicji7wRZ4VhuBz4y3nRs6WKcdqDeoU--HqIk/edit?pli=1#slide=id.g2580ba7db4c_1_0
