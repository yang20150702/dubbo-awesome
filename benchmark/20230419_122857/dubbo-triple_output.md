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
# Warmup Iteration   1: 1.010 ops/ms
# Warmup Iteration   2: 2.375 ops/ms
# Warmup Iteration   3: 5.058 ops/ms
Iteration   1: 5.620 ops/ms
Iteration   2: 5.962 ops/ms
Iteration   3: 6.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.892 ±(99.9%) 4.458 ops/ms [Average]
  (min, avg, max) = (5.620, 5.892, 6.094), stdev = 0.244
  CI (99.9%): [1.434, 10.349] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.670 ops/ms
# Warmup Iteration   2: 4.991 ops/ms
# Warmup Iteration   3: 6.134 ops/ms
Iteration   1: 6.277 ops/ms
Iteration   2: 6.408 ops/ms
Iteration   3: 6.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.339 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (6.277, 6.339, 6.408), stdev = 0.066
  CI (99.9%): [5.142, 7.536] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.473 ops/ms
# Warmup Iteration   2: 4.411 ops/ms
# Warmup Iteration   3: 5.712 ops/ms
Iteration   1: 5.810 ops/ms
Iteration   2: 5.851 ops/ms
Iteration   3: 5.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.843 ±(99.9%) 0.555 ops/ms [Average]
  (min, avg, max) = (5.810, 5.843, 5.869), stdev = 0.030
  CI (99.9%): [5.289, 6.398] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.469 ops/ms
# Warmup Iteration   2: 4.020 ops/ms
# Warmup Iteration   3: 5.039 ops/ms
Iteration   1: 5.051 ops/ms
Iteration   2: 5.180 ops/ms
Iteration   3: 4.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.051 ±(99.9%) 2.361 ops/ms [Average]
  (min, avg, max) = (4.921, 5.051, 5.180), stdev = 0.129
  CI (99.9%): [2.689, 7.412] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 19.187 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.501 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.581 ±(99.9%) 0.010 ms/op
Iteration   1: 5.026 ±(99.9%) 0.019 ms/op
Iteration   2: 5.290 ±(99.9%) 0.013 ms/op
Iteration   3: 5.548 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.288 ±(99.9%) 4.764 ms/op [Average]
  (min, avg, max) = (5.026, 5.288, 5.548), stdev = 0.261
  CI (99.9%): [0.524, 10.052] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.127 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.959 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.203 ±(99.9%) 0.008 ms/op
Iteration   1: 5.130 ±(99.9%) 0.009 ms/op
Iteration   2: 4.965 ±(99.9%) 0.016 ms/op
Iteration   3: 5.169 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.088 ±(99.9%) 1.974 ms/op [Average]
  (min, avg, max) = (4.965, 5.088, 5.169), stdev = 0.108
  CI (99.9%): [3.113, 7.062] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 18.281 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.053 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.623 ±(99.9%) 0.006 ms/op
Iteration   1: 5.357 ±(99.9%) 0.011 ms/op
Iteration   2: 5.640 ±(99.9%) 0.008 ms/op
Iteration   3: 5.192 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.396 ±(99.9%) 4.133 ms/op [Average]
  (min, avg, max) = (5.192, 5.396, 5.640), stdev = 0.227
  CI (99.9%): [1.263, 9.529] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.012 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.430 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.637 ±(99.9%) 0.017 ms/op
Iteration   1: 6.225 ±(99.9%) 0.021 ms/op
Iteration   2: 6.637 ±(99.9%) 0.014 ms/op
Iteration   3: 6.435 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.432 ±(99.9%) 3.753 ms/op [Average]
  (min, avg, max) = (6.225, 6.432, 6.637), stdev = 0.206
  CI (99.9%): [2.680, 10.185] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.373 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 7.945 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.166 ±(99.9%) 0.030 ms/op
Iteration   1: 5.570 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   7.122 ms/op
                 createUser·p0.95:   8.126 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  23.779 ms/op
                 createUser·p0.9999: 33.916 ms/op
                 createUser·p1.00:   36.438 ms/op

Iteration   2: 5.399 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.083 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   7.545 ms/op
                 createUser·p0.99:   9.667 ms/op
                 createUser·p0.999:  13.402 ms/op
                 createUser·p0.9999: 37.688 ms/op
                 createUser·p1.00:   38.797 ms/op

Iteration   3: 5.183 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.054 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.029 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  26.084 ms/op
                 createUser·p0.9999: 32.304 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178403
  mean =      5.379 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 79766 
    [ 5.000,  7.500) = 88896 
    [ 7.500, 10.000) = 7832 
    [10.000, 12.500) = 1362 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.076 ms/op
     p(99.9000) =     22.400 ms/op
     p(99.9900) =     35.717 ms/op
     p(99.9990) =     38.695 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.561 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 5.768 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.465 ±(99.9%) 0.024 ms/op
Iteration   1: 5.226 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.319 ms/op
                 existUser·p0.99:   9.945 ms/op
                 existUser·p0.999:  24.556 ms/op
                 existUser·p0.9999: 27.058 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   2: 5.202 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.216 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.242 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  13.665 ms/op
                 existUser·p0.9999: 31.719 ms/op
                 existUser·p1.00:   32.571 ms/op

Iteration   3: 5.319 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.339 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.542 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  30.368 ms/op
                 existUser·p0.9999: 50.200 ms/op
                 existUser·p1.00:   51.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182829
  mean =      5.249 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 92297 
    [ 5.000, 10.000) = 89024 
    [10.000, 15.000) = 1289 
    [15.000, 20.000) = 59 
    [20.000, 25.000) = 12 
    [25.000, 30.000) = 53 
    [30.000, 35.000) = 58 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 22 
    [50.000, 55.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     17.504 ms/op
     p(99.9900) =     49.068 ms/op
     p(99.9990) =     51.118 ms/op
     p(99.9999) =     51.118 ms/op
    p(100.0000) =     51.118 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.285 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.597 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.453 ±(99.9%) 0.019 ms/op
Iteration   1: 5.678 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   7.250 ms/op
                 getUser·p0.95:   8.733 ms/op
                 getUser·p0.99:   12.431 ms/op
                 getUser·p0.999:  23.902 ms/op
                 getUser·p0.9999: 27.767 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 5.457 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.474 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.945 ms/op
                 getUser·p0.999:  25.625 ms/op
                 getUser·p0.9999: 34.285 ms/op
                 getUser·p1.00:   36.438 ms/op

Iteration   3: 5.360 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.560 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.094 ms/op
                 getUser·p0.99:   10.264 ms/op
                 getUser·p0.999:  26.324 ms/op
                 getUser·p0.9999: 30.773 ms/op
                 getUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174549
  mean =      5.495 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 70813 
    [ 5.000,  7.500) = 92769 
    [ 7.500, 10.000) = 7938 
    [10.000, 12.500) = 1937 
    [12.500, 15.000) = 479 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     11.256 ms/op
     p(99.9000) =     25.199 ms/op
     p(99.9900) =     33.656 ms/op
     p(99.9990) =     36.340 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 18.714 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.572 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.617 ±(99.9%) 0.027 ms/op
Iteration   1: 6.377 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  23.521 ms/op
                 listUser·p0.9999: 26.574 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 6.328 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.892 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   8.948 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  28.818 ms/op
                 listUser·p0.9999: 32.238 ms/op
                 listUser·p1.00:   33.751 ms/op

Iteration   3: 6.459 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.941 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  21.872 ms/op
                 listUser·p0.9999: 26.380 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150225
  mean =      6.387 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 10817 
    [ 5.000,  7.500) = 120292 
    [ 7.500, 10.000) = 14010 
    [10.000, 12.500) = 3832 
    [12.500, 15.000) = 809 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.892 ms/op
     p(50.0000) =      6.038 ms/op
     p(90.0000) =      7.840 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     12.173 ms/op
     p(99.9000) =     25.395 ms/op
     p(99.9900) =     30.244 ms/op
     p(99.9990) =     33.488 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.892 ± 4.458  ops/ms
ClientPb.existUser                       thrpt       3   6.339 ± 1.197  ops/ms
ClientPb.getUser                         thrpt       3   5.843 ± 0.555  ops/ms
ClientPb.listUser                        thrpt       3   5.051 ± 2.361  ops/ms
ClientPb.createUser                       avgt       3   5.288 ± 4.764   ms/op
ClientPb.existUser                        avgt       3   5.088 ± 1.974   ms/op
ClientPb.getUser                          avgt       3   5.396 ± 4.133   ms/op
ClientPb.listUser                         avgt       3   6.432 ± 3.753   ms/op
ClientPb.createUser                     sample  178403   5.379 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.350           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.112           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.076           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.400           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.717           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.797           ms/op
ClientPb.existUser                      sample  182829   5.249 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.604           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.480           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.504           ms/op
ClientPb.existUser:existUser·p0.9999    sample          49.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          51.118           ms/op
ClientPb.getUser                        sample  174549   5.495 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.955           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.734           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.979           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.256           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.199           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.656           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438           ms/op
ClientPb.listUser                       sample  150225   6.387 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.038           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.840           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.173           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.395           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.244           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.751           ms/op
