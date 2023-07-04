# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.238 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 9.181 ops/ms
Iteration   2: 9.391 ops/ms
Iteration   3: 9.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.206 ±(99.9%) 3.164 ops/ms [Average]
  (min, avg, max) = (9.047, 9.206, 9.391), stdev = 0.173
  CI (99.9%): [6.042, 12.371] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.282 ops/ms
# Warmup Iteration   2: 8.642 ops/ms
# Warmup Iteration   3: 9.314 ops/ms
Iteration   1: 9.796 ops/ms
Iteration   2: 9.979 ops/ms
Iteration   3: 9.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.781 ±(99.9%) 3.766 ops/ms [Average]
  (min, avg, max) = (9.567, 9.781, 9.979), stdev = 0.206
  CI (99.9%): [6.015, 13.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.778 ops/ms
# Warmup Iteration   2: 7.697 ops/ms
# Warmup Iteration   3: 8.817 ops/ms
Iteration   1: 9.153 ops/ms
Iteration   2: 9.002 ops/ms
Iteration   3: 9.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.149 ±(99.9%) 2.643 ops/ms [Average]
  (min, avg, max) = (9.002, 9.149, 9.292), stdev = 0.145
  CI (99.9%): [6.506, 11.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.666 ops/ms
# Warmup Iteration   2: 7.031 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.904 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.054 ±(99.9%) 2.634 ops/ms [Average]
  (min, avg, max) = (7.904, 8.054, 8.192), stdev = 0.144
  CI (99.9%): [5.420, 10.688] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.805 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
Iteration   1: 3.359 ±(99.9%) 0.005 ms/op
Iteration   2: 3.535 ±(99.9%) 0.005 ms/op
Iteration   3: 3.314 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.402 ±(99.9%) 2.127 ms/op [Average]
  (min, avg, max) = (3.314, 3.402, 3.535), stdev = 0.117
  CI (99.9%): [1.275, 5.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.730 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.003 ms/op
Iteration   1: 3.290 ±(99.9%) 0.006 ms/op
Iteration   2: 3.392 ±(99.9%) 0.011 ms/op
Iteration   3: 3.372 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.351 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.290, 3.351, 3.392), stdev = 0.054
  CI (99.9%): [2.363, 4.340] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.966 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.003 ms/op
Iteration   1: 3.363 ±(99.9%) 0.008 ms/op
Iteration   2: 3.447 ±(99.9%) 0.007 ms/op
Iteration   3: 3.400 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.404 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (3.363, 3.404, 3.447), stdev = 0.042
  CI (99.9%): [2.636, 4.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.100 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.870 ±(99.9%) 0.014 ms/op
Iteration   2: 3.953 ±(99.9%) 0.013 ms/op
Iteration   3: 3.989 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.938 ±(99.9%) 1.120 ms/op [Average]
  (min, avg, max) = (3.870, 3.938, 3.989), stdev = 0.061
  CI (99.9%): [2.818, 5.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.327 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.014 ms/op
Iteration   1: 3.565 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  22.156 ms/op
                 createUser·p0.9999: 24.414 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 3.406 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  22.643 ms/op
                 createUser·p0.9999: 25.993 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.467 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 27.216 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275799
  mean =      3.478 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4004 
    [ 2.500,  5.000) = 264356 
    [ 5.000,  7.500) = 6272 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     20.323 ms/op
     p(99.9900) =     26.059 ms/op
     p(99.9990) =     28.204 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.564 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.011 ms/op
Iteration   1: 3.496 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  20.952 ms/op
                 existUser·p0.9999: 24.112 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  14.533 ms/op
                 existUser·p0.9999: 26.812 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   3: 3.394 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 27.315 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283391
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12428 
    [ 2.500,  5.000) = 264808 
    [ 5.000,  7.500) = 5464 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 107 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     10.735 ms/op
     p(99.9900) =     27.022 ms/op
     p(99.9990) =     28.443 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.361 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.012 ms/op
Iteration   1: 3.443 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  21.077 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  21.856 ms/op
                 getUser·p0.9999: 25.481 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 3.443 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.091 ms/op
                 getUser·p0.999:  9.374 ms/op
                 getUser·p0.9999: 26.120 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278789
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2244 
    [ 2.500,  5.000) = 267253 
    [ 5.000,  7.500) = 8123 
    [ 7.500, 10.000) = 732 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     18.750 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     26.563 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.345 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.013 ms/op
Iteration   1: 4.077 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  18.036 ms/op
                 listUser·p0.9999: 24.024 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   2: 4.082 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  16.377 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.143 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  15.401 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234278
  mean =      4.100 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 223776 
    [ 5.000,  7.500) = 8119 
    [ 7.500, 10.000) = 1603 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     23.401 ms/op
     p(99.9990) =     25.383 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.206 ± 3.164  ops/ms
ClientPb.existUser                       thrpt       3   9.781 ± 3.766  ops/ms
ClientPb.getUser                         thrpt       3   9.149 ± 2.643  ops/ms
ClientPb.listUser                        thrpt       3   8.054 ± 2.634  ops/ms
ClientPb.createUser                       avgt       3   3.402 ± 2.127   ms/op
ClientPb.existUser                        avgt       3   3.351 ± 0.988   ms/op
ClientPb.getUser                          avgt       3   3.404 ± 0.767   ms/op
ClientPb.listUser                         avgt       3   3.938 ± 1.120   ms/op
ClientPb.createUser                     sample  275799   3.478 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.028           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.160           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.323           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.059           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.606           ms/op
ClientPb.existUser                      sample  283391   3.386 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.909           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.735           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.022           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.508           ms/op
ClientPb.getUser                        sample  278789   3.442 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.305           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.116           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  234278   4.100 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.401           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.887           ms/op
