Starter code for CS4254/5565 Project 3.

This contains two separate environments -- one Docker based intended for both x86 and M1 OSX host systems, the other Virtualbox based for x86 Windows systems. If you're a Linux user, either one will work -- we'd recommend using the VM. To launch your environment, `cd` into the appropriate subdirectory to launch your environment according to the directions in each folder's README.md.

Latest Results:
Performance tests
  huge 5 Mb/s, 10 ms, 0% drop, 0% duplicate 0% delay        [DATAOK]
    0.998 sec elapsed, 976KB sent
    Rate: 7Mb/s                                             [ OKAY ]
  large 5 Mb/s, 10 ms, 10% drop, 0% duplicate 0% delay      [DATAOK]
    2.730 sec elapsed, 97KB sent
    Rate: 286Kb/s                                           [PERF2]
  large 5 Mb/s, 50 ms, 10% drop, 0% duplicate 0% delay      [DATAOK]
    5.025 sec elapsed, 97KB sent
    Rate: 155Kb/s                                           [PERF4]
  large 10 Mb/s, 25 ms, 10% drop, 10% duplicate 20% delay   [DATAOK]
    3.221 sec elapsed, 97KB sent
    Rate: 242Kb/s                                           [PERF3]


while(len(in_flight_packets) < WINDOW ):
    if( not send_next_packet()):
    while len(in_flight_packets) != 0 and EXPECTED_ACK_NUM not in in_flight_packets:
        EXPECTED_ACK_NUM+=1
    sock.sendto(in_flight_packets[EXPECTED_ACK_NUM].encode(), dest)
    break                                [PERF4]

Performance tests
  huge 5 Mb/s, 10 ms, 0% drop, 0% duplicate 0% delay        [DATAOK]
    1.102 sec elapsed, 976KB sent
    Rate: 6Mb/s                                             [ OKAY ]
  large 5 Mb/s, 10 ms, 10% drop, 0% duplicate 0% delay      [DATAOK]
    1.147 sec elapsed, 97KB sent
    Rate: 681Kb/s                                           [PERF20]
  large 5 Mb/s, 50 ms, 10% drop, 0% duplicate 0% delay      [DATAOK]
    3.547 sec elapsed, 97KB sent
    Rate: 220Kb/s                                           [PERF7]
  large 10 Mb/s, 25 ms, 10% drop, 10% duplicate 20% delay   [DATAOK]
    2.263 sec elapsed, 97KB sent
    Rate: 345Kb/s                                           [PERF5]