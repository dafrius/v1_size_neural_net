## Umut's schedule
- Umut paper - waiting on paper (beh stuff)

## To do before Matt leaves: V1 size project
- Document pipeline from fMRI prep / all the steps for pRFs -> maps (from
  scanner to V1 size value)
- Write the fMRI stuff into a methods section
- Scan and analyse new data
- Only if we have time: Making the above available on github in an open access
  way OSF

## Neural network we can hopefully get done
- 
- Discuss what the research question
- How to study effect of 'V1 size/RF size' on contextual modulation?
- Do we need to retrain a network from scratch?

  Us    AlexNet    Us
:----|-----------|----:

- AlexNet we have to keep as is - i.e. pretrained
- To change the RF/V1 size, that requires retraining... so we have to keep the
  'Us' part of the network pipeline small and manageable
- Change size of stimulus??
- If we shrink the content of the image (keeping the physical size constant
  e.g. 200 x 200 pixels), that corresponds to a small V1 (and therefore
  relatively bigger RFs)
- How to measure contextual modulation of the network?
- Maybe train a network (with FB layer) to classify circle size (small, medium,
  large) and then see how it handles the same circles but with surround (that
  should create the size illusion)?
- We could have a FF only control network (maybe AlexNet, but with N+1 layers
  to 'replace' the FB layer we had before)
