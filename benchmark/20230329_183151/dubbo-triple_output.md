# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.555 ops/ms
# Warmup Iteration   2: 6.576 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 9.832 ops/ms
Iteration   2: 9.798 ops/ms
Iteration   3: 10.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.947 ±(99.9%) 4.163 ops/ms [Average]
  (min, avg, max) = (9.798, 9.947, 10.209), stdev = 0.228
  CI (99.9%): [5.784, 14.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.807 ops/ms
# Warmup Iteration   2: 9.634 ops/ms
# Warmup Iteration   3: 10.639 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.686 ±(99.9%) 2.703 ops/ms [Average]
  (min, avg, max) = (10.530, 10.686, 10.825), stdev = 0.148
  CI (99.9%): [7.983, 13.390] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.441 ops/ms
# Warmup Iteration   2: 9.531 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 9.984 ops/ms
Iteration   2: 9.589 ops/ms
Iteration   3: 9.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.849 ±(99.9%) 4.110 ops/ms [Average]
  (min, avg, max) = (9.589, 9.849, 9.984), stdev = 0.225
  CI (99.9%): [5.739, 13.959] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ops/ms
# Warmup Iteration   2: 7.778 ops/ms
# Warmup Iteration   3: 8.819 ops/ms
Iteration   1: 8.407 ops/ms
Iteration   2: 8.464 ops/ms
Iteration   3: 8.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.514 ±(99.9%) 2.549 ops/ms [Average]
  (min, avg, max) = (8.407, 8.514, 8.672), stdev = 0.140
  CI (99.9%): [5.966, 11.063] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.327 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.006 ms/op
Iteration   1: 3.267 ±(99.9%) 0.007 ms/op
Iteration   2: 3.245 ±(99.9%) 0.007 ms/op
Iteration   3: 3.159 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.224 ±(99.9%) 1.036 ms/op [Average]
  (min, avg, max) = (3.159, 3.224, 3.267), stdev = 0.057
  CI (99.9%): [2.188, 4.259] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.499 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.006 ms/op
Iteration   1: 3.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.051 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (3.007, 3.051, 3.088), stdev = 0.041
  CI (99.9%): [2.304, 3.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.264 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.003 ms/op
Iteration   1: 3.204 ±(99.9%) 0.007 ms/op
Iteration   2: 3.190 ±(99.9%) 0.004 ms/op
Iteration   3: 3.101 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.165 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.101, 3.165, 3.204), stdev = 0.056
  CI (99.9%): [2.147, 4.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.235 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.004 ms/op
Iteration   1: 3.668 ±(99.9%) 0.010 ms/op
Iteration   2: 3.743 ±(99.9%) 0.004 ms/op
Iteration   3: 3.779 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.730 ±(99.9%) 1.034 ms/op [Average]
  (min, avg, max) = (3.668, 3.730, 3.779), stdev = 0.057
  CI (99.9%): [2.696, 4.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.773 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
Iteration   1: 3.248 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.379 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  19.089 ms/op
                 createUser·p0.9999: 26.252 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  10.791 ms/op
                 createUser·p0.9999: 23.821 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  14.070 ms/op
                 createUser·p0.9999: 20.905 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299082
  mean =      3.207 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28868 
    [ 2.500,  5.000) = 264411 
    [ 5.000,  7.500) = 5137 
    [ 7.500, 10.000) = 265 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     23.563 ms/op
     p(99.9990) =     26.478 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.187 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
Iteration   1: 3.090 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  10.135 ms/op
                 existUser·p0.9999: 20.185 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.014 ms/op
                 existUser·p0.999:  11.944 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  8.345 ms/op
                 existUser·p0.9999: 20.244 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306662
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27794 
    [ 2.500,  5.000) = 273173 
    [ 5.000,  7.500) = 5043 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     25.930 ms/op
     p(99.9990) =     28.047 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.933 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  16.220 ms/op
                 getUser·p0.9999: 19.695 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  9.482 ms/op
                 getUser·p0.9999: 24.116 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  10.551 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302400
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11516 
    [ 2.500,  5.000) = 284316 
    [ 5.000,  7.500) = 5707 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     22.438 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.856 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.011 ms/op
Iteration   1: 3.747 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.505 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  14.773 ms/op
                 listUser·p0.9999: 23.247 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 3.660 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.141 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.337 ms/op
                 listUser·p0.9999: 14.251 ms/op
                 listUser·p1.00:   15.516 ms/op

Iteration   3: 3.719 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  12.747 ms/op
                 listUser·p0.9999: 13.959 ms/op
                 listUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258903
  mean =      3.708 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 252012 
    [ 5.000,  7.500) = 4878 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     13.207 ms/op
     p(99.9900) =     18.789 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.947 ± 4.163  ops/ms
ClientPb.existUser                       thrpt       3  10.686 ± 2.703  ops/ms
ClientPb.getUser                         thrpt       3   9.849 ± 4.110  ops/ms
ClientPb.listUser                        thrpt       3   8.514 ± 2.549  ops/ms
ClientPb.createUser                       avgt       3   3.224 ± 1.036   ms/op
ClientPb.existUser                        avgt       3   3.051 ± 0.746   ms/op
ClientPb.getUser                          avgt       3   3.165 ± 1.018   ms/op
ClientPb.listUser                         avgt       3   3.730 ± 1.034   ms/op
ClientPb.createUser                     sample  299082   3.207 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.379           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.811           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.563           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.739           ms/op
ClientPb.existUser                      sample  306662   3.127 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.895           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.930           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  302400   3.175 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.977           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.713           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.438           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.838           ms/op
ClientPb.listUser                       sample  258903   3.708 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.505           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.592           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.207           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.789           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.495           ms/op
