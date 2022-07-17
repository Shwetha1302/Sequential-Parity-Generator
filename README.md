# Sequential-Parity-Generator
  Used to check the parity(even or odd) of a binary number before and after manipulation.

WHAT IS PARITY BIT?
  The parity generating technique is one of the most widely used error detection techniques for the data transmission. In digital systems, when
binary data is transmitted and processed, data may be subjected to noise so that such noise can alter 0s (of data bits) to 1s and 1s to 0s.
  Hence, a Parity Bit is aded to the word containing data in order to make number of 1s either even or odd. The message containing the data bits along with parity bit is transmitted from transmitter to the receiver.
  At the receiving end, the number of 1s in the message is counted and if it doesn’t match with the transmitted one, it means there is an error in the data. Thus, the Parity Bit it is used to detect errors, during the transmission of binary data.

HOW PARITY CHECKING WORKS?
  Assume, for example, that two devices are communicating with even parity (the most common form of parity checking). As the transmitting device sends data, it counts the number of set bits in each group of seven bits. If the number of set bits is even, it sets the parity bit to 0; if the number of set bits is odd, it sets the parity bit to 1. In this way, every byte has an even number of set bits. On the receiving side, the device checks each byte to make sure that it has an even number of set bits. If it finds an odd number of set bits, the receiver knows there was an error during transmission.
  The sender and receiver must both agree to use parity checking and to agree on whether parity is to be odd or even. If the two sides are not configured with the same parity sense, communication will be impossible.
