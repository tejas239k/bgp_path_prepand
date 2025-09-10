# bgp_path_prepand
Route manipulation using as_path prepand. Here to reach to the loopback interface 4.4.4.4/24 on R4 the R3 was choosing 35.1.1.3 route as their best path, but if want to force them to use the 25.1.1.2 path then as_path prepand is configure on R4 on the outbound traffic.
