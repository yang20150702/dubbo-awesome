# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.546 ops/ms
# Warmup Iteration   2: 3.214 ops/ms
# Warmup Iteration   3: 5.220 ops/ms
Iteration   1: 7.476 ops/ms
Iteration   2: 7.857 ops/ms
Iteration   3: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.738 ±(99.9%) 4.157 ops/ms [Average]
  (min, avg, max) = (7.476, 7.738, 7.883), stdev = 0.228
  CI (99.9%): [3.581, 11.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.252 ops/ms
# Warmup Iteration   2: 6.673 ops/ms
# Warmup Iteration   3: 8.075 ops/ms
Iteration   1: 8.426 ops/ms
Iteration   2: 8.408 ops/ms
Iteration   3: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.481 ±(99.9%) 2.021 ops/ms [Average]
  (min, avg, max) = (8.408, 8.481, 8.608), stdev = 0.111
  CI (99.9%): [6.460, 10.502] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.295 ops/ms
# Warmup Iteration   2: 6.252 ops/ms
# Warmup Iteration   3: 7.611 ops/ms
Iteration   1: 7.458 ops/ms
Iteration   2: 7.492 ops/ms
Iteration   3: 8.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.658 ±(99.9%) 5.776 ops/ms [Average]
  (min, avg, max) = (7.458, 7.658, 8.023), stdev = 0.317
  CI (99.9%): [1.882, 13.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.003 ops/ms
# Warmup Iteration   2: 5.492 ops/ms
# Warmup Iteration   3: 6.379 ops/ms
Iteration   1: 6.352 ops/ms
Iteration   2: 6.562 ops/ms
Iteration   3: 6.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.552 ±(99.9%) 3.548 ops/ms [Average]
  (min, avg, max) = (6.352, 6.552, 6.741), stdev = 0.194
  CI (99.9%): [3.004, 10.100] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.359 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.853 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.006 ms/op
Iteration   1: 4.309 ±(99.9%) 0.004 ms/op
Iteration   2: 4.100 ±(99.9%) 0.011 ms/op
Iteration   3: 4.033 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.147 ±(99.9%) 2.630 ms/op [Average]
  (min, avg, max) = (4.033, 4.147, 4.309), stdev = 0.144
  CI (99.9%): [1.517, 6.777] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.855 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.549 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.005 ms/op
Iteration   1: 3.943 ±(99.9%) 0.005 ms/op
Iteration   2: 3.871 ±(99.9%) 0.007 ms/op
Iteration   3: 3.875 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.896 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (3.871, 3.896, 3.943), stdev = 0.041
  CI (99.9%): [3.154, 4.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.680 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.011 ms/op
Iteration   1: 4.038 ±(99.9%) 0.003 ms/op
Iteration   2: 4.014 ±(99.9%) 0.012 ms/op
Iteration   3: 4.035 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.029 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (4.014, 4.029, 4.038), stdev = 0.013
  CI (99.9%): [3.791, 4.268] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.350 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.224 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.848 ±(99.9%) 0.012 ms/op
Iteration   1: 4.746 ±(99.9%) 0.008 ms/op
Iteration   2: 4.725 ±(99.9%) 0.011 ms/op
Iteration   3: 4.875 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.782 ±(99.9%) 1.486 ms/op [Average]
  (min, avg, max) = (4.725, 4.782, 4.875), stdev = 0.081
  CI (99.9%): [3.296, 6.268] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.222 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.208 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.462 ±(99.9%) 0.019 ms/op
Iteration   1: 4.048 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  12.450 ms/op
                 createUser·p0.9999: 30.477 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   2: 4.163 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.485 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  27.104 ms/op
                 createUser·p0.9999: 31.010 ms/op
                 createUser·p1.00:   32.244 ms/op

Iteration   3: 4.096 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.587 ms/op
                 createUser·p0.999:  15.450 ms/op
                 createUser·p0.9999: 37.759 ms/op
                 createUser·p1.00:   39.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234027
  mean =      4.101 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 292 
    [ 2.500,  5.000) = 217747 
    [ 5.000,  7.500) = 13381 
    [ 7.500, 10.000) = 1786 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     15.743 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     38.251 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.918 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.014 ms/op
Iteration   1: 3.837 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  12.696 ms/op
                 existUser·p0.9999: 25.745 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   2: 3.891 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.985 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   7.276 ms/op
                 existUser·p0.999:  14.677 ms/op
                 existUser·p0.9999: 33.154 ms/op
                 existUser·p1.00:   33.686 ms/op

Iteration   3: 3.957 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   7.561 ms/op
                 existUser·p0.999:  27.604 ms/op
                 existUser·p0.9999: 31.982 ms/op
                 existUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246307
  mean =      3.894 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 228 
    [ 2.500,  5.000) = 235599 
    [ 5.000,  7.500) = 8190 
    [ 7.500, 10.000) = 1297 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     16.459 ms/op
     p(99.9900) =     32.604 ms/op
     p(99.9990) =     33.506 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.767 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.898 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.461 ±(99.9%) 0.016 ms/op
Iteration   1: 4.224 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   8.380 ms/op
                 getUser·p0.999:  25.766 ms/op
                 getUser·p0.9999: 33.105 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.718 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  11.125 ms/op
                 getUser·p0.9999: 27.533 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 4.032 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   8.192 ms/op
                 getUser·p0.999:  25.942 ms/op
                 getUser·p0.9999: 32.913 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234608
  mean =      4.090 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 217802 
    [ 5.000,  7.500) = 13838 
    [ 7.500, 10.000) = 1803 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 138 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     25.526 ms/op
     p(99.9900) =     32.539 ms/op
     p(99.9990) =     33.771 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.528 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.227 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.925 ±(99.9%) 0.020 ms/op
Iteration   1: 4.638 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  25.299 ms/op
                 listUser·p0.9999: 27.299 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   2: 4.675 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  18.404 ms/op
                 listUser·p0.9999: 21.468 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 4.779 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.300 ms/op
                 listUser·p0.99:   9.340 ms/op
                 listUser·p0.999:  16.879 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204185
  mean =      4.697 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 172544 
    [ 5.000,  7.500) = 26427 
    [ 7.500, 10.000) = 3825 
    [10.000, 12.500) = 654 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      9.112 ms/op
     p(99.9000) =     18.475 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     28.732 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.738 ± 4.157  ops/ms
ClientPb.existUser                       thrpt       3   8.481 ± 2.021  ops/ms
ClientPb.getUser                         thrpt       3   7.658 ± 5.776  ops/ms
ClientPb.listUser                        thrpt       3   6.552 ± 3.548  ops/ms
ClientPb.createUser                       avgt       3   4.147 ± 2.630   ms/op
ClientPb.existUser                        avgt       3   3.896 ± 0.742   ms/op
ClientPb.getUser                          avgt       3   4.029 ± 0.238   ms/op
ClientPb.listUser                         avgt       3   4.782 ± 1.486   ms/op
ClientPb.createUser                     sample  234027   4.101 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.485           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.792           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.766           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.743           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.979           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.715           ms/op
ClientPb.existUser                      sample  246307   3.894 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.597           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.459           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.604           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.686           ms/op
ClientPb.getUser                        sample  234608   4.090 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.374           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.382           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.881           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.526           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.539           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.603           ms/op
ClientPb.listUser                       sample  204185   4.697 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.946           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.226           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.112           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.475           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.771           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.164           ms/op
