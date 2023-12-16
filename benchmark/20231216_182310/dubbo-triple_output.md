# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.935 ops/ms
# Warmup Iteration   2: 11.830 ops/ms
# Warmup Iteration   3: 11.891 ops/ms
Iteration   1: 12.188 ops/ms
Iteration   2: 12.259 ops/ms
Iteration   3: 12.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.232 ±(99.9%) 0.711 ops/ms [Average]
  (min, avg, max) = (12.188, 12.232, 12.259), stdev = 0.039
  CI (99.9%): [11.522, 12.943] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 7.937 ops/ms
# Warmup Iteration   2: 12.817 ops/ms
# Warmup Iteration   3: 12.817 ops/ms
Iteration   1: 12.938 ops/ms
Iteration   2: 12.758 ops/ms
Iteration   3: 12.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.823 ±(99.9%) 1.820 ops/ms [Average]
  (min, avg, max) = (12.758, 12.823, 12.938), stdev = 0.100
  CI (99.9%): [11.003, 14.642] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.767 ops/ms
# Warmup Iteration   2: 12.402 ops/ms
# Warmup Iteration   3: 12.782 ops/ms
Iteration   1: 12.714 ops/ms
Iteration   2: 12.492 ops/ms
Iteration   3: 12.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.643 ±(99.9%) 2.374 ops/ms [Average]
  (min, avg, max) = (12.492, 12.643, 12.722), stdev = 0.130
  CI (99.9%): [10.268, 15.017] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.461 ops/ms
# Warmup Iteration   2: 10.333 ops/ms
# Warmup Iteration   3: 10.565 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.613 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.581 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (10.561, 10.581, 10.613), stdev = 0.028
  CI (99.9%): [10.070, 11.091] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.604 ±(99.9%) 0.004 ms/op
Iteration   1: 2.633 ±(99.9%) 0.005 ms/op
Iteration   2: 2.587 ±(99.9%) 0.003 ms/op
Iteration   3: 2.591 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.604 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (2.587, 2.604, 2.633), stdev = 0.026
  CI (99.9%): [2.138, 3.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.628 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.515 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.503, 2.515, 2.533), stdev = 0.015
  CI (99.9%): [2.235, 2.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.778 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.520 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.522 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.514, 2.522, 2.532), stdev = 0.009
  CI (99.9%): [2.352, 2.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.794 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.005 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
Iteration   3: 3.029 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (3.029, 3.035, 3.045), stdev = 0.009
  CI (99.9%): [2.877, 3.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.465 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.795 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
Iteration   1: 2.575 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  11.745 ms/op
                 createUser·p0.9999: 13.707 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 2.593 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 12.605 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.587 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 11.736 ms/op
                 createUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371050
  mean =      2.585 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 175825 
    [ 2.500,  3.750) = 190173 
    [ 3.750,  5.000) = 4209 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     13.366 ms/op
     p(99.9990) =     13.896 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  12.201 ms/op
                 existUser·p0.9999: 14.238 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.561 ms/op
                 existUser·p0.999:  6.128 ms/op
                 existUser·p0.9999: 12.484 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  9.154 ms/op
                 existUser·p0.9999: 12.387 ms/op
                 existUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387227
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 192669 
    [ 2.500,  3.750) = 190794 
    [ 3.750,  5.000) = 2991 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     14.013 ms/op
     p(99.9990) =     14.738 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.685 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  11.754 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  9.127 ms/op
                 getUser·p0.9999: 14.361 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   3: 2.580 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  6.942 ms/op
                 getUser·p0.9999: 9.889 ms/op
                 getUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372732
  mean =      2.573 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 179149 
    [ 2.500,  3.750) = 188329 
    [ 3.750,  5.000) = 4191 
    [ 5.000,  6.250) = 595 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      7.373 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     15.033 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.009 ms/op
Iteration   1: 3.094 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.915 ms/op
                 listUser·p0.999:  9.497 ms/op
                 listUser·p0.9999: 11.054 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  10.076 ms/op
                 listUser·p0.9999: 12.616 ms/op
                 listUser·p1.00:   13.009 ms/op

Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.514 ms/op
                 listUser·p0.9999: 11.748 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312246
  mean =      3.072 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 80541 
    [ 2.500,  3.750) = 188879 
    [ 3.750,  5.000) = 34381 
    [ 5.000,  6.250) = 6875 
    [ 6.250,  7.500) = 747 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 201 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     12.882 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.232 ± 0.711  ops/ms
ClientPb.existUser                       thrpt       3  12.823 ± 1.820  ops/ms
ClientPb.getUser                         thrpt       3  12.643 ± 2.374  ops/ms
ClientPb.listUser                        thrpt       3  10.581 ± 0.511  ops/ms
ClientPb.createUser                       avgt       3   2.604 ± 0.465   ms/op
ClientPb.existUser                        avgt       3   2.515 ± 0.281   ms/op
ClientPb.getUser                          avgt       3   2.522 ± 0.170   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.158   ms/op
ClientPb.createUser                     sample  371050   2.585 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.366           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.844           ms/op
ClientPb.existUser                      sample  387227   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.726           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.013           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  372732   2.573 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.769           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.373           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.894           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.221           ms/op
ClientPb.listUser                       sample  312246   3.072 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.828           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.650           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.813           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.009           ms/op
