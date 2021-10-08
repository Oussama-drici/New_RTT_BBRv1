BBRv1 does not perform well in variation of bandwidth scenario compared to cubic, so we 
have tried to improve the BBRv1 in this scenario. The amelioration in TCP is based in the packet-
processing delay, as we know that bbr use round-trip time to calculate the BDP multiplied
by the bottleneck bandwidth, but we have a little time that we can profit in sending of
data, this time is known as the packet-processing time, when the sender receives the
acknowledgments of the transmitted data, it waits a time to process the receive data and
to process the next data that it want to send, after that the data is transmitted, so the
link is not perfectly utilized in this processing time, we have suggested to adds this time
in the calculation of the minimum round-trip time or as it's called the RTprop to get
more improvement in throughput.

Regards,

Computer Systems Enginner Drici Oussama.

For any information contact me at o.drici@esi-sba.dz
