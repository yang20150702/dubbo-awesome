# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.175 ops/ms
# Warmup Iteration   2: 11.829 ops/ms
# Warmup Iteration   3: 12.347 ops/ms
Iteration   1: 12.560 ops/ms
Iteration   2: 12.612 ops/ms
Iteration   3: 12.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.604 ±(99.9%) 0.735 ops/ms [Average]
  (min, avg, max) = (12.560, 12.604, 12.639), stdev = 0.040
  CI (99.9%): [11.869, 13.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.555 ops/ms
# Warmup Iteration   2: 12.956 ops/ms
# Warmup Iteration   3: 13.060 ops/ms
Iteration   1: 12.997 ops/ms
Iteration   2: 13.045 ops/ms
Iteration   3: 13.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.018 ±(99.9%) 0.456 ops/ms [Average]
  (min, avg, max) = (12.997, 13.018, 13.045), stdev = 0.025
  CI (99.9%): [12.562, 13.473] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.180 ops/ms
# Warmup Iteration   2: 12.459 ops/ms
# Warmup Iteration   3: 12.778 ops/ms
Iteration   1: 12.988 ops/ms
Iteration   2: 12.980 ops/ms
Iteration   3: 12.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.987 ±(99.9%) 0.108 ops/ms [Average]
  (min, avg, max) = (12.980, 12.987, 12.992), stdev = 0.006
  CI (99.9%): [12.879, 13.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.596 ops/ms
# Warmup Iteration   2: 10.438 ops/ms
# Warmup Iteration   3: 10.548 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.704 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.656 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (10.597, 10.656, 10.704), stdev = 0.054
  CI (99.9%): [9.668, 11.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.558 ±(99.9%) 0.003 ms/op
Iteration   3: 2.547 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.534, 2.546, 2.558), stdev = 0.012
  CI (99.9%): [2.321, 2.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.003 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.492 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.482, 2.492, 2.506), stdev = 0.013
  CI (99.9%): [2.261, 2.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.003 ms/op
Iteration   3: 2.530 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.495, 2.513, 2.530), stdev = 0.018
  CI (99.9%): [2.189, 2.836] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.724 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
Iteration   3: 3.013 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (3.013, 3.014, 3.017), stdev = 0.002
  CI (99.9%): [2.973, 3.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.109 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.568 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  11.412 ms/op
                 createUser·p0.9999: 15.770 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  9.319 ms/op
                 createUser·p0.9999: 12.025 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 10.429 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374653
  mean =      2.559 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 178900 
    [ 2.500,  3.750) = 190739 
    [ 3.750,  5.000) = 3887 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     14.690 ms/op
     p(99.9990) =     16.106 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.675 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  10.816 ms/op
                 existUser·p0.9999: 13.955 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  6.855 ms/op
                 existUser·p0.9999: 12.814 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.602 ms/op
                 existUser·p0.999:  5.657 ms/op
                 existUser·p0.9999: 13.135 ms/op
                 existUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385968
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 189828 
    [ 2.500,  3.750) = 193520 
    [ 3.750,  5.000) = 1951 
    [ 5.000,  6.250) = 250 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.523 ms/op
     p(99.9000) =      6.013 ms/op
     p(99.9900) =     13.163 ms/op
     p(99.9990) =     14.191 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  5.383 ms/op
                 getUser·p0.9999: 13.310 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.090 ms/op
                 getUser·p0.999:  8.597 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  8.973 ms/op
                 getUser·p0.9999: 11.695 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377814
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 185808 
    [ 2.500,  3.750) = 186726 
    [ 3.750,  5.000) = 4070 
    [ 5.000,  6.250) = 754 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      6.318 ms/op
     p(99.9900) =     13.331 ms/op
     p(99.9990) =     14.187 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.545 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.690 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.519 ms/op
                 listUser·p0.999:  9.035 ms/op
                 listUser·p0.9999: 10.494 ms/op
                 listUser·p1.00:   11.059 ms/op

Iteration   2: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 13.061 ms/op
                 listUser·p1.00:   14.254 ms/op

Iteration   3: 2.942 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.264 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.947 ms/op
                 listUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324095
  mean =      2.959 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 102832 
    [ 2.500,  3.750) = 185635 
    [ 3.750,  5.000) = 29079 
    [ 5.000,  6.250) = 5268 
    [ 6.250,  7.500) = 513 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.141 ms/op
     p(99.9900) =     12.474 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.604 ± 0.735  ops/ms
ClientPb.existUser                       thrpt       3  13.018 ± 0.456  ops/ms
ClientPb.getUser                         thrpt       3  12.987 ± 0.108  ops/ms
ClientPb.listUser                        thrpt       3  10.656 ± 0.988  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   2.492 ± 0.231   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.323   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.041   ms/op
ClientPb.createUser                     sample  374653   2.559 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.877           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.864           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.690           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.793           ms/op
ClientPb.existUser                      sample  385968   2.486 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.887           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.013           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.163           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  377814   2.539 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.318           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.287           ms/op
ClientPb.listUser                       sample  324095   2.959 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.141           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.474           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.254           ms/op
