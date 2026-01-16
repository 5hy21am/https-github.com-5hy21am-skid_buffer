# skid_buffer
-- Skid Buffer is the smallest buffer which can be used between two pipeline stages. It isolates the ready/stall path to relax timi ng. It acts like an elastic buffer which stores the valid data when the receiver applies backpressure to the sender.

-- Pipeline Skid Buffer can be used as the smallest buffer (depth-2) between pipeline stages, with complete isolation of valid & ready for better timing relaxation at slightly increased area cost.

Source codes included
---------------------
-- Skid Buffer

-- Pipeline Skid Buffer
