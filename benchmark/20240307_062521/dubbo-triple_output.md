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
# Warmup Iteration   1: 4.726 ops/ms
# Warmup Iteration   2: 12.501 ops/ms
# Warmup Iteration   3: 12.627 ops/ms
Iteration   1: 12.984 ops/ms
Iteration   2: 13.053 ops/ms
Iteration   3: 13.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.032 ±(99.9%) 0.753 ops/ms [Average]
  (min, avg, max) = (12.984, 13.032, 13.058), stdev = 0.041
  CI (99.9%): [12.279, 13.784] (assumes normal distribution)


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
# Warmup Iteration   1: 8.628 ops/ms
# Warmup Iteration   2: 13.376 ops/ms
# Warmup Iteration   3: 13.294 ops/ms
Iteration   1: 13.304 ops/ms
Iteration   2: 13.560 ops/ms
Iteration   3: 13.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.412 ±(99.9%) 2.422 ops/ms [Average]
  (min, avg, max) = (13.304, 13.412, 13.560), stdev = 0.133
  CI (99.9%): [10.990, 15.834] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.922 ops/ms
# Warmup Iteration   2: 12.741 ops/ms
# Warmup Iteration   3: 13.245 ops/ms
Iteration   1: 13.146 ops/ms
Iteration   2: 12.828 ops/ms
Iteration   3: 13.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.056 ±(99.9%) 3.639 ops/ms [Average]
  (min, avg, max) = (12.828, 13.056, 13.195), stdev = 0.199
  CI (99.9%): [9.418, 16.695] (assumes normal distribution)


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
# Warmup Iteration   1: 6.531 ops/ms
# Warmup Iteration   2: 10.620 ops/ms
# Warmup Iteration   3: 10.717 ops/ms
Iteration   1: 10.681 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.655 ±(99.9%) 0.458 ops/ms [Average]
  (min, avg, max) = (10.631, 10.655, 10.681), stdev = 0.025
  CI (99.9%): [10.197, 11.114] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.003 ms/op
Iteration   2: 2.501 ±(99.9%) 0.003 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.503 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.490, 2.503, 2.519), stdev = 0.015
  CI (99.9%): [2.233, 2.773] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.444 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.437, 2.444, 2.459), stdev = 0.012
  CI (99.9%): [2.221, 2.668] (assumes normal distribution)


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.003 ms/op
Iteration   1: 2.390 ±(99.9%) 0.004 ms/op
Iteration   2: 2.379 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.396 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.379, 2.396, 2.419), stdev = 0.020
  CI (99.9%): [2.024, 2.767] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.782 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
Iteration   3: 3.003 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.979, 2.997, 3.009), stdev = 0.016
  CI (99.9%): [2.705, 3.289] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  11.205 ms/op
                 createUser·p0.9999: 14.045 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  9.271 ms/op
                 createUser·p0.9999: 12.702 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.157 ms/op
                 createUser·p0.9999: 11.947 ms/op
                 createUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383076
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 186369 
    [ 2.500,  3.750) = 192757 
    [ 3.750,  5.000) = 2838 
    [ 5.000,  6.250) = 578 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     14.350 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.403 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.379 ±(99.9%) 0.005 ms/op
Iteration   1: 2.376 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.863 ms/op
                 existUser·p0.95:   2.945 ms/op
                 existUser·p0.99:   3.297 ms/op
                 existUser·p0.999:  5.713 ms/op
                 existUser·p0.9999: 14.263 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.530 ms/op
                 existUser·p0.999:  5.380 ms/op
                 existUser·p0.9999: 10.923 ms/op
                 existUser·p1.00:   11.239 ms/op

Iteration   3: 2.392 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  6.979 ms/op
                 existUser·p0.9999: 10.961 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401456
  mean =      2.389 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 200779 
    [ 2.500,  3.750) = 197896 
    [ 3.750,  5.000) = 2148 
    [ 5.000,  6.250) = 202 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =      6.014 ms/op
     p(99.9900) =     13.236 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.006 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  6.567 ms/op
                 getUser·p0.9999: 13.334 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  6.604 ms/op
                 getUser·p0.9999: 12.464 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  7.755 ms/op
                 getUser·p0.9999: 16.229 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 394091
  mean =      2.434 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 200064 
    [ 2.500,  3.750) = 189909 
    [ 3.750,  5.000) = 3017 
    [ 5.000,  6.250) = 624 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      6.612 ms/op
     p(99.9900) =     13.415 ms/op
     p(99.9990) =     16.713 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.009 ms/op
Iteration   1: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.548 ms/op
                 listUser·p0.999:  8.512 ms/op
                 listUser·p0.9999: 10.346 ms/op
                 listUser·p1.00:   10.682 ms/op

Iteration   2: 2.927 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.752 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.081 ms/op
                 listUser·p0.9999: 13.076 ms/op
                 listUser·p1.00:   13.681 ms/op

Iteration   3: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.381 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 12.631 ms/op
                 listUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 326125
  mean =      2.941 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 107670 
    [ 2.500,  3.750) = 181995 
    [ 3.750,  5.000) = 29136 
    [ 5.000,  6.250) = 6006 
    [ 6.250,  7.500) = 489 
    [ 7.500,  8.750) = 269 
    [ 8.750, 10.000) = 203 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     12.851 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.032 ± 0.753  ops/ms
ClientPb.existUser                       thrpt       3  13.412 ± 2.422  ops/ms
ClientPb.getUser                         thrpt       3  13.056 ± 3.639  ops/ms
ClientPb.listUser                        thrpt       3  10.655 ± 0.458  ops/ms
ClientPb.createUser                       avgt       3   2.503 ± 0.270   ms/op
ClientPb.existUser                        avgt       3   2.444 ± 0.223   ms/op
ClientPb.getUser                          avgt       3   2.396 ± 0.372   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.292   ms/op
ClientPb.createUser                     sample  383076   2.504 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.970           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.257           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.549           ms/op
ClientPb.existUser                      sample  401456   2.389 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.888           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.014           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.236           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.680           ms/op
ClientPb.getUser                        sample  394091   2.434 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.785           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.612           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.415           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.876           ms/op
ClientPb.listUser                       sample  326125   2.941 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.851           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.681           ms/op
