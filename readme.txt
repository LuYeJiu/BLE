The function getLatency() is the proposed algorithm to calculate average latency and worst-case latency. The function getLatency() invokes the function cut_the_tail(). 

The function monte_carlo() is used to calculate worst-case latency and average latency by monte-carlo simulation on condition that worst-case latency is finite. You can replicate the experiments and find that the results of monte-carlo simulation are always very close to those of the proposed algorithm.

mean_time_record is used to record the mean computation time.
create_figure is used to draw a figure showing the latencies for given parameters. You can also compared the results of the proposed algorithm with those of monte-carlo simulation in this figure.
