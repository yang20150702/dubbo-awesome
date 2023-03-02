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
# Warmup Iteration   1: 1.070 ops/ms
# Warmup Iteration   2: 2.541 ops/ms
# Warmup Iteration   3: 5.133 ops/ms
Iteration   1: 5.353 ops/ms
Iteration   2: 5.704 ops/ms
Iteration   3: 6.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.691 ±(99.9%) 6.053 ops/ms [Average]
  (min, avg, max) = (5.353, 5.691, 6.016), stdev = 0.332
  CI (99.9%): [≈ 0, 11.744] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.521 ops/ms
# Warmup Iteration   2: 4.938 ops/ms
# Warmup Iteration   3: 5.845 ops/ms
Iteration   1: 6.168 ops/ms
Iteration   2: 5.809 ops/ms
Iteration   3: 6.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.002 ±(99.9%) 3.311 ops/ms [Average]
  (min, avg, max) = (5.809, 6.002, 6.168), stdev = 0.181
  CI (99.9%): [2.691, 9.313] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.373 ops/ms
# Warmup Iteration   2: 4.099 ops/ms
# Warmup Iteration   3: 5.450 ops/ms
Iteration   1: 5.642 ops/ms
Iteration   2: 5.396 ops/ms
Iteration   3: 5.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.536 ±(99.9%) 2.313 ops/ms [Average]
  (min, avg, max) = (5.396, 5.536, 5.642), stdev = 0.127
  CI (99.9%): [3.223, 7.849] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.443 ops/ms
# Warmup Iteration   2: 3.906 ops/ms
# Warmup Iteration   3: 4.864 ops/ms
Iteration   1: 4.667 ops/ms
Iteration   2: 4.636 ops/ms
Iteration   3: 4.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.664 ±(99.9%) 0.486 ops/ms [Average]
  (min, avg, max) = (4.636, 4.664, 4.689), stdev = 0.027
  CI (99.9%): [4.178, 5.149] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 20.139 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 6.994 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 6.514 ±(99.9%) 0.014 ms/op
Iteration   1: 6.195 ±(99.9%) 0.010 ms/op
Iteration   2: 6.232 ±(99.9%) 0.011 ms/op
Iteration   3: 5.906 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.111 ±(99.9%) 3.255 ms/op [Average]
  (min, avg, max) = (5.906, 6.111, 6.232), stdev = 0.178
  CI (99.9%): [2.856, 9.365] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.448 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.779 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.732 ±(99.9%) 0.010 ms/op
Iteration   1: 5.548 ±(99.9%) 0.016 ms/op
Iteration   2: 5.806 ±(99.9%) 0.010 ms/op
Iteration   3: 5.642 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.665 ±(99.9%) 2.382 ms/op [Average]
  (min, avg, max) = (5.548, 5.665, 5.806), stdev = 0.131
  CI (99.9%): [3.283, 8.047] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.160 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.129 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.170 ±(99.9%) 0.006 ms/op
Iteration   1: 5.935 ±(99.9%) 0.007 ms/op
Iteration   2: 6.088 ±(99.9%) 0.011 ms/op
Iteration   3: 5.694 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.906 ±(99.9%) 3.620 ms/op [Average]
  (min, avg, max) = (5.694, 5.906, 6.088), stdev = 0.198
  CI (99.9%): [2.286, 9.525] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.626 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.677 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.516 ±(99.9%) 0.018 ms/op
Iteration   1: 7.027 ±(99.9%) 0.011 ms/op
Iteration   2: 6.624 ±(99.9%) 0.016 ms/op
Iteration   3: 6.413 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.688 ±(99.9%) 5.684 ms/op [Average]
  (min, avg, max) = (6.413, 6.688, 7.027), stdev = 0.312
  CI (99.9%): [1.004, 12.372] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.485 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 7.432 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.045 ±(99.9%) 0.026 ms/op
Iteration   1: 5.515 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.650 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  24.973 ms/op
                 createUser·p0.9999: 28.023 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   2: 5.761 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.355 ms/op
                 createUser·p0.50:   5.546 ms/op
                 createUser·p0.90:   7.111 ms/op
                 createUser·p0.95:   7.823 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 31.373 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   3: 5.775 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.757 ms/op
                 createUser·p0.50:   5.521 ms/op
                 createUser·p0.90:   7.119 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   11.497 ms/op
                 createUser·p0.999:  30.202 ms/op
                 createUser·p0.9999: 34.171 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168886
  mean =      5.681 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 50163 
    [ 5.000,  7.500) = 107669 
    [ 7.500, 10.000) = 8998 
    [10.000, 12.500) = 1231 
    [12.500, 15.000) = 441 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.355 ms/op
     p(50.0000) =      5.399 ms/op
     p(90.0000) =      7.004 ms/op
     p(95.0000) =      7.791 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     20.553 ms/op
     p(99.9900) =     33.394 ms/op
     p(99.9990) =     34.610 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.130 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.136 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.572 ±(99.9%) 0.017 ms/op
Iteration   1: 5.401 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.454 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.865 ms/op
                 existUser·p0.95:   7.741 ms/op
                 existUser·p0.99:   9.601 ms/op
                 existUser·p0.999:  24.003 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 5.575 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.773 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   7.062 ms/op
                 existUser·p0.95:   7.913 ms/op
                 existUser·p0.99:   10.121 ms/op
                 existUser·p0.999:  26.509 ms/op
                 existUser·p0.9999: 29.000 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   3: 5.377 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.646 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   10.093 ms/op
                 existUser·p0.999:  15.433 ms/op
                 existUser·p0.9999: 30.215 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176183
  mean =      5.450 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 77963 
    [ 5.000,  7.500) = 87885 
    [ 7.500, 10.000) = 8525 
    [10.000, 12.500) = 1217 
    [12.500, 15.000) = 335 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.454 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      7.766 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     29.733 ms/op
     p(99.9990) =     30.482 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.850 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 7.266 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.039 ±(99.9%) 0.024 ms/op
Iteration   1: 6.272 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.740 ms/op
                 getUser·p0.50:   5.931 ms/op
                 getUser·p0.90:   7.910 ms/op
                 getUser·p0.95:   9.634 ms/op
                 getUser·p0.99:   12.796 ms/op
                 getUser·p0.999:  22.577 ms/op
                 getUser·p0.9999: 27.980 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 5.821 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   3.125 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.094 ms/op
                 getUser·p0.95:   8.077 ms/op
                 getUser·p0.99:   11.141 ms/op
                 getUser·p0.999:  24.496 ms/op
                 getUser·p0.9999: 42.730 ms/op
                 getUser·p1.00:   43.319 ms/op

Iteration   3: 6.060 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.417 ms/op
                 getUser·p0.50:   5.857 ms/op
                 getUser·p0.90:   7.602 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   9.912 ms/op
                 getUser·p0.999:  24.642 ms/op
                 getUser·p0.9999: 27.685 ms/op
                 getUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 158776
  mean =      6.046 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 34899 
    [ 5.000, 10.000) = 120243 
    [10.000, 15.000) = 3150 
    [15.000, 20.000) = 281 
    [20.000, 25.000) = 77 
    [25.000, 30.000) = 94 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      2.417 ms/op
     p(50.0000) =      5.734 ms/op
     p(90.0000) =      7.528 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.780 ms/op
     p(99.9000) =     23.666 ms/op
     p(99.9900) =     42.140 ms/op
     p(99.9990) =     43.165 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.219 ±(99.9%) 0.352 ms/op
# Warmup Iteration   2: 8.018 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 7.473 ±(99.9%) 0.032 ms/op
Iteration   1: 6.954 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   6.513 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   13.435 ms/op
                 listUser·p0.999:  29.131 ms/op
                 listUser·p0.9999: 31.916 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 6.805 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.256 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   11.436 ms/op
                 listUser·p0.999:  30.638 ms/op
                 listUser·p0.9999: 39.884 ms/op
                 listUser·p1.00:   40.632 ms/op

Iteration   3: 6.585 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.998 ms/op
                 listUser·p0.999:  27.881 ms/op
                 listUser·p0.9999: 33.114 ms/op
                 listUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141671
  mean =      6.778 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2302 
    [ 5.000, 10.000) = 134487 
    [10.000, 15.000) = 4263 
    [15.000, 20.000) = 280 
    [20.000, 25.000) = 66 
    [25.000, 30.000) = 159 
    [30.000, 35.000) = 98 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      6.398 ms/op
     p(90.0000) =      8.094 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     12.550 ms/op
     p(99.9000) =     29.164 ms/op
     p(99.9900) =     36.012 ms/op
     p(99.9990) =     40.523 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.691 ± 6.053  ops/ms
ClientPb.existUser                       thrpt       3   6.002 ± 3.311  ops/ms
ClientPb.getUser                         thrpt       3   5.536 ± 2.313  ops/ms
ClientPb.listUser                        thrpt       3   4.664 ± 0.486  ops/ms
ClientPb.createUser                       avgt       3   6.111 ± 3.255   ms/op
ClientPb.existUser                        avgt       3   5.665 ± 2.382   ms/op
ClientPb.getUser                          avgt       3   5.906 ± 3.620   ms/op
ClientPb.listUser                         avgt       3   6.688 ± 5.684   ms/op
ClientPb.createUser                     sample  168886   5.681 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.355           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.004           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.791           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.420           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.553           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.394           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  176183   5.450 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.071           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.766           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.027           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.579           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.733           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  158776   6.046 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.417           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.503           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.780           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.666           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.140           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.319           ms/op
ClientPb.listUser                       sample  141671   6.778 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.398           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.550           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.164           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.012           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.632           ms/op
