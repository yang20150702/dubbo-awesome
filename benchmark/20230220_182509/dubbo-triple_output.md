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
# Warmup Iteration   1: 0.892 ops/ms
# Warmup Iteration   2: 1.880 ops/ms
# Warmup Iteration   3: 4.029 ops/ms
Iteration   1: 5.059 ops/ms
Iteration   2: 5.116 ops/ms
Iteration   3: 5.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.166 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (5.059, 5.166, 5.321), stdev = 0.138
  CI (99.9%): [2.652, 7.679] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.405 ops/ms
# Warmup Iteration   2: 4.128 ops/ms
# Warmup Iteration   3: 5.454 ops/ms
Iteration   1: 5.498 ops/ms
Iteration   2: 5.581 ops/ms
Iteration   3: 5.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.471 ±(99.9%) 2.299 ops/ms [Average]
  (min, avg, max) = (5.333, 5.471, 5.581), stdev = 0.126
  CI (99.9%): [3.172, 7.769] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.229 ops/ms
# Warmup Iteration   2: 3.192 ops/ms
# Warmup Iteration   3: 5.333 ops/ms
Iteration   1: 5.294 ops/ms
Iteration   2: 5.198 ops/ms
Iteration   3: 5.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.301 ±(99.9%) 1.955 ops/ms [Average]
  (min, avg, max) = (5.198, 5.301, 5.412), stdev = 0.107
  CI (99.9%): [3.346, 7.256] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.142 ops/ms
# Warmup Iteration   2: 3.055 ops/ms
# Warmup Iteration   3: 4.204 ops/ms
Iteration   1: 4.362 ops/ms
Iteration   2: 4.695 ops/ms
Iteration   3: 4.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.547 ±(99.9%) 3.093 ops/ms [Average]
  (min, avg, max) = (4.362, 4.547, 4.695), stdev = 0.170
  CI (99.9%): [1.454, 7.640] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 23.034 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 8.369 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.248 ±(99.9%) 0.010 ms/op
Iteration   1: 6.258 ±(99.9%) 0.012 ms/op
Iteration   2: 5.920 ±(99.9%) 0.013 ms/op
Iteration   3: 5.809 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.996 ±(99.9%) 4.269 ms/op [Average]
  (min, avg, max) = (5.809, 5.996, 6.258), stdev = 0.234
  CI (99.9%): [1.726, 10.265] (assumes normal distribution)


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
# Warmup Iteration   1: 20.025 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.328 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.004 ±(99.9%) 0.008 ms/op
Iteration   1: 5.722 ±(99.9%) 0.015 ms/op
Iteration   2: 5.772 ±(99.9%) 0.012 ms/op
Iteration   3: 5.767 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.754 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (5.722, 5.754, 5.772), stdev = 0.027
  CI (99.9%): [5.252, 6.255] (assumes normal distribution)


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
# Warmup Iteration   1: 21.519 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.819 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.051 ±(99.9%) 0.010 ms/op
Iteration   1: 5.754 ±(99.9%) 0.014 ms/op
Iteration   2: 5.823 ±(99.9%) 0.019 ms/op
Iteration   3: 5.691 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.756 ±(99.9%) 1.202 ms/op [Average]
  (min, avg, max) = (5.691, 5.756, 5.823), stdev = 0.066
  CI (99.9%): [4.554, 6.958] (assumes normal distribution)


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
# Warmup Iteration   1: 22.800 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.893 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.943 ±(99.9%) 0.021 ms/op
Iteration   1: 6.827 ±(99.9%) 0.017 ms/op
Iteration   2: 6.730 ±(99.9%) 0.013 ms/op
Iteration   3: 6.621 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.726 ±(99.9%) 1.881 ms/op [Average]
  (min, avg, max) = (6.621, 6.726, 6.827), stdev = 0.103
  CI (99.9%): [4.845, 8.607] (assumes normal distribution)


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
# Warmup Iteration   1: 20.653 ±(99.9%) 0.392 ms/op
# Warmup Iteration   2: 8.293 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 6.600 ±(99.9%) 0.036 ms/op
Iteration   1: 5.932 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.609 ms/op
                 createUser·p0.50:   5.644 ms/op
                 createUser·p0.90:   7.381 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.404 ms/op
                 createUser·p0.999:  25.406 ms/op
                 createUser·p0.9999: 29.761 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   2: 5.910 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.515 ms/op
                 createUser·p0.50:   5.628 ms/op
                 createUser·p0.90:   7.315 ms/op
                 createUser·p0.95:   8.372 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  24.409 ms/op
                 createUser·p0.9999: 30.854 ms/op
                 createUser·p1.00:   33.391 ms/op

Iteration   3: 5.965 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.732 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   12.261 ms/op
                 createUser·p0.999:  31.031 ms/op
                 createUser·p0.9999: 38.791 ms/op
                 createUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161652
  mean =      5.936 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 29329 
    [ 5.000, 10.000) = 128998 
    [10.000, 15.000) = 2837 
    [15.000, 20.000) = 292 
    [20.000, 25.000) = 21 
    [25.000, 30.000) = 96 
    [30.000, 35.000) = 54 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.515 ms/op
     p(50.0000) =      5.620 ms/op
     p(90.0000) =      7.365 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     26.149 ms/op
     p(99.9900) =     37.224 ms/op
     p(99.9990) =     40.057 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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
# Warmup Iteration   1: 19.529 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 6.933 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.813 ±(99.9%) 0.021 ms/op
Iteration   1: 5.672 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.462 ms/op
                 existUser·p0.50:   5.349 ms/op
                 existUser·p0.90:   7.119 ms/op
                 existUser·p0.95:   8.118 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  27.093 ms/op
                 existUser·p0.9999: 31.399 ms/op
                 existUser·p1.00:   35.848 ms/op

Iteration   2: 5.601 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   7.012 ms/op
                 existUser·p0.95:   8.167 ms/op
                 existUser·p0.99:   11.518 ms/op
                 existUser·p0.999:  17.269 ms/op
                 existUser·p0.9999: 30.615 ms/op
                 existUser·p1.00:   32.178 ms/op

Iteration   3: 5.678 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   7.209 ms/op
                 existUser·p0.95:   8.217 ms/op
                 existUser·p0.99:   11.194 ms/op
                 existUser·p0.999:  29.872 ms/op
                 existUser·p0.9999: 33.751 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 169855
  mean =      5.650 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 53934 
    [ 5.000,  7.500) = 102977 
    [ 7.500, 10.000) = 10169 
    [10.000, 12.500) = 1845 
    [12.500, 15.000) = 537 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     18.739 ms/op
     p(99.9900) =     32.408 ms/op
     p(99.9990) =     35.345 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 20.550 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 7.240 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.210 ±(99.9%) 0.027 ms/op
Iteration   1: 6.029 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   3.138 ms/op
                 getUser·p0.50:   5.661 ms/op
                 getUser·p0.90:   7.561 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   12.124 ms/op
                 getUser·p0.999:  17.885 ms/op
                 getUser·p0.9999: 36.398 ms/op
                 getUser·p1.00:   40.632 ms/op

Iteration   2: 6.107 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   5.644 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   9.208 ms/op
                 getUser·p0.99:   14.402 ms/op
                 getUser·p0.999:  26.792 ms/op
                 getUser·p0.9999: 31.162 ms/op
                 getUser·p1.00:   31.621 ms/op

Iteration   3: 6.112 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.945 ms/op
                 getUser·p0.50:   5.644 ms/op
                 getUser·p0.90:   7.995 ms/op
                 getUser·p0.95:   9.667 ms/op
                 getUser·p0.99:   12.656 ms/op
                 getUser·p0.999:  30.114 ms/op
                 getUser·p0.9999: 33.817 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 157781
  mean =      6.082 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 26561 
    [ 5.000, 10.000) = 125706 
    [10.000, 15.000) = 4762 
    [15.000, 20.000) = 562 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 63 
    [30.000, 35.000) = 78 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      9.208 ms/op
     p(99.0000) =     13.173 ms/op
     p(99.9000) =     25.894 ms/op
     p(99.9900) =     35.601 ms/op
     p(99.9990) =     39.610 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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
# Warmup Iteration   1: 25.775 ±(99.9%) 0.455 ms/op
# Warmup Iteration   2: 8.987 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 7.562 ±(99.9%) 0.039 ms/op
Iteration   1: 7.142 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   6.701 ms/op
                 listUser·p0.90:   8.978 ms/op
                 listUser·p0.95:   10.404 ms/op
                 listUser·p0.99:   13.859 ms/op
                 listUser·p0.999:  30.284 ms/op
                 listUser·p0.9999: 35.882 ms/op
                 listUser·p1.00:   36.635 ms/op

Iteration   2: 6.999 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.084 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.815 ms/op
                 listUser·p0.95:   10.306 ms/op
                 listUser·p0.99:   14.631 ms/op
                 listUser·p0.999:  33.576 ms/op
                 listUser·p0.9999: 36.139 ms/op
                 listUser·p1.00:   37.290 ms/op

Iteration   3: 6.743 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.129 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  31.246 ms/op
                 listUser·p0.9999: 35.717 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137955
  mean =      6.957 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 2851 
    [ 5.000,  7.500) = 106875 
    [ 7.500, 10.000) = 21117 
    [10.000, 12.500) = 5047 
    [12.500, 15.000) = 1166 
    [15.000, 17.500) = 504 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 103 
    [35.000, 37.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      6.496 ms/op
     p(90.0000) =      8.651 ms/op
     p(95.0000) =     10.060 ms/op
     p(99.0000) =     13.599 ms/op
     p(99.9000) =     32.506 ms/op
     p(99.9900) =     35.796 ms/op
     p(99.9990) =     37.041 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.166 ± 2.513  ops/ms
ClientPb.existUser                       thrpt       3   5.471 ± 2.299  ops/ms
ClientPb.getUser                         thrpt       3   5.301 ± 1.955  ops/ms
ClientPb.listUser                        thrpt       3   4.547 ± 3.093  ops/ms
ClientPb.createUser                       avgt       3   5.996 ± 4.269   ms/op
ClientPb.existUser                        avgt       3   5.754 ± 0.502   ms/op
ClientPb.getUser                          avgt       3   5.756 ± 1.202   ms/op
ClientPb.listUser                         avgt       3   6.726 ± 1.881   ms/op
ClientPb.createUser                     sample  161652   5.936 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.365           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.454           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.567           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.149           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.224           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.501           ms/op
ClientPb.existUser                      sample  169855   5.650 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.733           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.119           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.167           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.190           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.739           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.408           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.848           ms/op
ClientPb.getUser                        sample  157781   6.082 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.985           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.208           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.173           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.894           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.601           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.632           ms/op
ClientPb.listUser                       sample  137955   6.957 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.060           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.599           ms/op
ClientPb.listUser:listUser·p0.999       sample          32.506           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.796           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.290           ms/op
