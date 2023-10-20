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
# Warmup Iteration   1: 1.884 ops/ms
# Warmup Iteration   2: 4.144 ops/ms
# Warmup Iteration   3: 7.491 ops/ms
Iteration   1: 7.481 ops/ms
Iteration   2: 7.864 ops/ms
Iteration   3: 7.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.751 ±(99.9%) 4.289 ops/ms [Average]
  (min, avg, max) = (7.481, 7.751, 7.908), stdev = 0.235
  CI (99.9%): [3.462, 12.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.428 ops/ms
# Warmup Iteration   2: 7.151 ops/ms
# Warmup Iteration   3: 8.254 ops/ms
Iteration   1: 8.133 ops/ms
Iteration   2: 8.390 ops/ms
Iteration   3: 8.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.260 ±(99.9%) 2.345 ops/ms [Average]
  (min, avg, max) = (8.133, 8.260, 8.390), stdev = 0.129
  CI (99.9%): [5.915, 10.605] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.424 ops/ms
# Warmup Iteration   2: 7.276 ops/ms
# Warmup Iteration   3: 8.025 ops/ms
Iteration   1: 8.071 ops/ms
Iteration   2: 8.323 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.169 ±(99.9%) 2.464 ops/ms [Average]
  (min, avg, max) = (8.071, 8.169, 8.323), stdev = 0.135
  CI (99.9%): [5.705, 10.633] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 5.512 ops/ms
# Warmup Iteration   3: 6.538 ops/ms
Iteration   1: 6.879 ops/ms
Iteration   2: 6.770 ops/ms
Iteration   3: 6.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.766 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (6.650, 6.766, 6.879), stdev = 0.115
  CI (99.9%): [4.676, 8.857] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.217 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.308 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.003 ms/op
Iteration   1: 4.110 ±(99.9%) 0.003 ms/op
Iteration   2: 4.017 ±(99.9%) 0.006 ms/op
Iteration   3: 3.954 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.027 ±(99.9%) 1.429 ms/op [Average]
  (min, avg, max) = (3.954, 4.027, 4.110), stdev = 0.078
  CI (99.9%): [2.598, 5.456] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.328 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.004 ms/op
Iteration   1: 3.876 ±(99.9%) 0.004 ms/op
Iteration   2: 3.964 ±(99.9%) 0.003 ms/op
Iteration   3: 3.798 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.879 ±(99.9%) 1.516 ms/op [Average]
  (min, avg, max) = (3.798, 3.879, 3.964), stdev = 0.083
  CI (99.9%): [2.363, 5.395] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.257 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.005 ms/op
Iteration   1: 4.052 ±(99.9%) 0.005 ms/op
Iteration   2: 4.028 ±(99.9%) 0.005 ms/op
Iteration   3: 4.064 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.048 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (4.028, 4.048, 4.064), stdev = 0.018
  CI (99.9%): [3.712, 4.383] (assumes normal distribution)


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
# Warmup Iteration   1: 14.292 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.159 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.808 ±(99.9%) 0.007 ms/op
Iteration   1: 4.794 ±(99.9%) 0.009 ms/op
Iteration   2: 4.548 ±(99.9%) 0.012 ms/op
Iteration   3: 4.570 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.637 ±(99.9%) 2.489 ms/op [Average]
  (min, avg, max) = (4.548, 4.637, 4.794), stdev = 0.136
  CI (99.9%): [2.149, 7.126] (assumes normal distribution)


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
# Warmup Iteration   1: 11.900 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 5.346 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.527 ±(99.9%) 0.020 ms/op
Iteration   1: 4.015 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   7.840 ms/op
                 createUser·p0.999:  23.888 ms/op
                 createUser·p0.9999: 26.216 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   2: 4.070 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   7.897 ms/op
                 createUser·p0.999:  14.104 ms/op
                 createUser·p0.9999: 27.593 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 3.987 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.747 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  29.066 ms/op
                 createUser·p0.9999: 38.011 ms/op
                 createUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238679
  mean =      4.024 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 842 
    [ 2.500,  5.000) = 222279 
    [ 5.000,  7.500) = 13071 
    [ 7.500, 10.000) = 1758 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     23.888 ms/op
     p(99.9900) =     37.023 ms/op
     p(99.9990) =     38.539 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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
# Warmup Iteration   1: 11.775 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.011 ms/op
Iteration   1: 3.736 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  21.430 ms/op
                 existUser·p0.9999: 23.604 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.862 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  18.612 ms/op
                 existUser·p0.9999: 27.145 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   3: 3.818 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  24.944 ms/op
                 existUser·p0.9999: 27.173 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252108
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 799 
    [ 2.500,  5.000) = 241812 
    [ 5.000,  7.500) = 7990 
    [ 7.500, 10.000) = 884 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     21.161 ms/op
     p(99.9900) =     26.837 ms/op
     p(99.9990) =     28.554 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 12.627 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.019 ms/op
Iteration   1: 4.160 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   8.241 ms/op
                 getUser·p0.999:  18.188 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 4.132 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   8.356 ms/op
                 getUser·p0.999:  18.566 ms/op
                 getUser·p0.9999: 25.043 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 4.138 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  23.593 ms/op
                 getUser·p0.9999: 27.010 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231630
  mean =      4.143 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 118 
    [ 2.500,  5.000) = 218581 
    [ 5.000,  7.500) = 9875 
    [ 7.500, 10.000) = 2275 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     20.315 ms/op
     p(99.9900) =     25.614 ms/op
     p(99.9990) =     27.330 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 15.008 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.803 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.880 ±(99.9%) 0.017 ms/op
Iteration   1: 4.795 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   8.850 ms/op
                 listUser·p0.999:  25.068 ms/op
                 listUser·p0.9999: 27.503 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 4.845 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 20.585 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 4.839 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  18.575 ms/op
                 listUser·p0.9999: 31.272 ms/op
                 listUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198748
  mean =      4.826 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 150660 
    [ 5.000,  7.500) = 43303 
    [ 7.500, 10.000) = 3688 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     20.652 ms/op
     p(99.9900) =     28.754 ms/op
     p(99.9990) =     32.181 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.751 ± 4.289  ops/ms
ClientPb.existUser                       thrpt       3   8.260 ± 2.345  ops/ms
ClientPb.getUser                         thrpt       3   8.169 ± 2.464  ops/ms
ClientPb.listUser                        thrpt       3   6.766 ± 2.090  ops/ms
ClientPb.createUser                       avgt       3   4.027 ± 1.429   ms/op
ClientPb.existUser                        avgt       3   3.879 ± 1.516   ms/op
ClientPb.getUser                          avgt       3   4.048 ± 0.335   ms/op
ClientPb.listUser                         avgt       3   4.637 ± 2.489   ms/op
ClientPb.createUser                     sample  238679   4.024 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.586           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.888           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.023           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.059           ms/op
ClientPb.existUser                      sample  252108   3.805 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.313           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.161           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.837           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.934           ms/op
ClientPb.getUser                        sample  231630   4.143 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.128           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.004           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.315           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.614           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.427           ms/op
ClientPb.listUser                       sample  198748   4.826 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.438           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.652           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.754           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.408           ms/op
