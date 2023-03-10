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
# Warmup Iteration   1: 1.950 ops/ms
# Warmup Iteration   2: 5.626 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 9.299 ops/ms
Iteration   2: 9.661 ops/ms
Iteration   3: 9.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.523 ±(99.9%) 3.565 ops/ms [Average]
  (min, avg, max) = (9.299, 9.523, 9.661), stdev = 0.195
  CI (99.9%): [5.958, 13.089] (assumes normal distribution)


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
# Warmup Iteration   1: 3.266 ops/ms
# Warmup Iteration   2: 9.167 ops/ms
# Warmup Iteration   3: 10.009 ops/ms
Iteration   1: 9.811 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 9.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.943 ±(99.9%) 7.185 ops/ms [Average]
  (min, avg, max) = (9.632, 9.943, 10.386), stdev = 0.394
  CI (99.9%): [2.758, 17.128] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.860 ops/ms
# Warmup Iteration   2: 8.236 ops/ms
# Warmup Iteration   3: 9.347 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 9.694 ops/ms
Iteration   3: 9.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.651 ±(99.9%) 0.960 ops/ms [Average]
  (min, avg, max) = (9.593, 9.651, 9.694), stdev = 0.053
  CI (99.9%): [8.691, 10.612] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.849 ops/ms
# Warmup Iteration   2: 7.367 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 8.179 ops/ms
Iteration   2: 8.085 ops/ms
Iteration   3: 8.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.202 ±(99.9%) 2.354 ops/ms [Average]
  (min, avg, max) = (8.085, 8.202, 8.340), stdev = 0.129
  CI (99.9%): [5.848, 10.555] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.942 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.005 ms/op
Iteration   1: 3.387 ±(99.9%) 0.007 ms/op
Iteration   2: 3.386 ±(99.9%) 0.006 ms/op
Iteration   3: 3.310 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.361 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.310, 3.361, 3.387), stdev = 0.044
  CI (99.9%): [2.550, 4.172] (assumes normal distribution)


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
# Warmup Iteration   1: 8.417 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.428 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.002 ms/op
Iteration   1: 3.259 ±(99.9%) 0.005 ms/op
Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
Iteration   3: 3.153 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.187 ±(99.9%) 1.136 ms/op [Average]
  (min, avg, max) = (3.150, 3.187, 3.259), stdev = 0.062
  CI (99.9%): [2.052, 4.323] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.518 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.008 ms/op
Iteration   1: 3.420 ±(99.9%) 0.005 ms/op
Iteration   2: 3.410 ±(99.9%) 0.006 ms/op
Iteration   3: 3.351 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.394 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.351, 3.394, 3.420), stdev = 0.037
  CI (99.9%): [2.717, 4.070] (assumes normal distribution)


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
# Warmup Iteration   1: 10.940 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.011 ms/op
Iteration   1: 3.921 ±(99.9%) 0.013 ms/op
Iteration   2: 3.943 ±(99.9%) 0.007 ms/op
Iteration   3: 3.832 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.899 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.832, 3.899, 3.943), stdev = 0.059
  CI (99.9%): [2.824, 4.973] (assumes normal distribution)


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
# Warmup Iteration   1: 9.367 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.010 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  20.414 ms/op
                 createUser·p0.9999: 28.135 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 26.006 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.333 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.841 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  16.760 ms/op
                 createUser·p0.9999: 24.943 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283756
  mean =      3.382 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9371 
    [ 2.500,  5.000) = 268347 
    [ 5.000,  7.500) = 5167 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     26.104 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 8.517 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.008 ms/op
Iteration   1: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  19.937 ms/op
                 existUser·p0.9999: 25.180 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   2: 3.293 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.541 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  13.419 ms/op
                 existUser·p0.9999: 25.175 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 27.288 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290791
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14161 
    [ 2.500,  5.000) = 270816 
    [ 5.000,  7.500) = 5039 
    [ 7.500, 10.000) = 382 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     13.052 ms/op
     p(99.9900) =     25.690 ms/op
     p(99.9990) =     28.002 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 8.254 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.009 ms/op
Iteration   1: 3.465 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  17.250 ms/op
                 getUser·p0.9999: 19.300 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  17.482 ms/op
                 getUser·p0.9999: 27.911 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  17.802 ms/op
                 getUser·p0.9999: 27.016 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281188
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14171 
    [ 2.500,  5.000) = 258077 
    [ 5.000,  7.500) = 7728 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     27.423 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 9.665 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.013 ms/op
Iteration   1: 3.974 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.407 ms/op
                 listUser·p0.9999: 28.825 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 4.053 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.998 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  16.356 ms/op
                 listUser·p0.9999: 18.351 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239419
  mean =      4.008 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 230725 
    [ 5.000,  7.500) = 6295 
    [ 7.500, 10.000) = 1427 
    [10.000, 12.500) = 375 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     24.875 ms/op
     p(99.9990) =     29.355 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.523 ± 3.565  ops/ms
ClientPb.existUser                       thrpt       3   9.943 ± 7.185  ops/ms
ClientPb.getUser                         thrpt       3   9.651 ± 0.960  ops/ms
ClientPb.listUser                        thrpt       3   8.202 ± 2.354  ops/ms
ClientPb.createUser                       avgt       3   3.361 ± 0.811   ms/op
ClientPb.existUser                        avgt       3   3.187 ± 1.136   ms/op
ClientPb.getUser                          avgt       3   3.394 ± 0.677   ms/op
ClientPb.listUser                         avgt       3   3.899 ± 1.075   ms/op
ClientPb.createUser                     sample  283756   3.382 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.039           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.104           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  290791   3.298 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.497           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.052           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.690           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  281188   3.414 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.035           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.423           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.901           ms/op
ClientPb.listUser                       sample  239419   4.008 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.187           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.875           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.557           ms/op
