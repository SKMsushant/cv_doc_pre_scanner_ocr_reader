# Problem Statement: 
 #### Prevent hazy, blurred, cropped, wrong-type, or mismatched KYC document uploads from reaching downstream Fintech manual review or paid verification workflows.

# Target Caller: 
#### Fintech's own web/mobile backend (B2B microservice).

# Latency SLA: 
#### <= 1–2 seconds total per HTTP request on CPU.

# Success Metrics: 
#### accuracy>=95% Recall>=95% on bad/failed documents (minimizing False Negatives where unreadable/mismatched documents slip through), tracked alongside Precision, F1-score, and per-stage failure rates.