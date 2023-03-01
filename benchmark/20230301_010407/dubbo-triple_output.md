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
# Warmup Iteration   1: 1.841 ops/ms
# Warmup Iteration   2: 5.016 ops/ms
# Warmup Iteration   3: 8.746 ops/ms
Iteration   1: 9.120 ops/ms
Iteration   2: 9.213 ops/ms
Iteration   3: 9.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.298 ±(99.9%) 4.240 ops/ms [Average]
  (min, avg, max) = (9.120, 9.298, 9.561), stdev = 0.232
  CI (99.9%): [5.058, 13.537] (assumes normal distribution)


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
# Warmup Iteration   1: 2.875 ops/ms
# Warmup Iteration   2: 8.318 ops/ms
# Warmup Iteration   3: 9.648 ops/ms
Iteration   1: 9.741 ops/ms
Iteration   2: 9.647 ops/ms
Iteration   3: 9.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.676 ±(99.9%) 1.019 ops/ms [Average]
  (min, avg, max) = (9.641, 9.676, 9.741), stdev = 0.056
  CI (99.9%): [8.657, 10.696] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ops/ms
# Warmup Iteration   2: 8.536 ops/ms
# Warmup Iteration   3: 9.355 ops/ms
Iteration   1: 9.264 ops/ms
Iteration   2: 9.721 ops/ms
Iteration   3: 9.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.452 ±(99.9%) 4.357 ops/ms [Average]
  (min, avg, max) = (9.264, 9.452, 9.721), stdev = 0.239
  CI (99.9%): [5.095, 13.810] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.081 ops/ms
# Warmup Iteration   2: 7.518 ops/ms
# Warmup Iteration   3: 7.741 ops/ms
Iteration   1: 7.984 ops/ms
Iteration   2: 8.090 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.066 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (7.984, 8.066, 8.124), stdev = 0.073
  CI (99.9%): [6.739, 9.393] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.511 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.006 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
Iteration   2: 3.460 ±(99.9%) 0.007 ms/op
Iteration   3: 3.273 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.354 ±(99.9%) 1.748 ms/op [Average]
  (min, avg, max) = (3.273, 3.354, 3.460), stdev = 0.096
  CI (99.9%): [1.606, 5.102] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.280 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.003 ms/op
Iteration   1: 3.209 ±(99.9%) 0.009 ms/op
Iteration   2: 3.291 ±(99.9%) 0.007 ms/op
Iteration   3: 3.403 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.301 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (3.209, 3.301, 3.403), stdev = 0.097
  CI (99.9%): [1.525, 5.077] (assumes normal distribution)


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
# Warmup Iteration   1: 8.773 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.004 ms/op
Iteration   1: 3.584 ±(99.9%) 0.004 ms/op
Iteration   2: 3.417 ±(99.9%) 0.008 ms/op
Iteration   3: 3.354 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.451 ±(99.9%) 2.164 ms/op [Average]
  (min, avg, max) = (3.354, 3.451, 3.584), stdev = 0.119
  CI (99.9%): [1.287, 5.616] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.603 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.007 ms/op
Iteration   1: 4.003 ±(99.9%) 0.005 ms/op
Iteration   2: 4.009 ±(99.9%) 0.005 ms/op
Iteration   3: 3.876 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.963 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.876, 3.963, 4.009), stdev = 0.075
  CI (99.9%): [2.590, 5.335] (assumes normal distribution)


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
# Warmup Iteration   1: 10.337 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.014 ms/op
Iteration   1: 3.279 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  10.936 ms/op
                 createUser·p0.9999: 25.567 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   2: 3.526 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  23.930 ms/op
                 createUser·p0.9999: 26.573 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  20.661 ms/op
                 createUser·p0.9999: 27.723 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282987
  mean =      3.391 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8358 
    [ 2.500,  5.000) = 269107 
    [ 5.000,  7.500) = 4369 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     26.434 ms/op
     p(99.9990) =     28.372 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 10.169 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
Iteration   1: 3.354 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  9.104 ms/op
                 existUser·p0.9999: 24.821 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   2: 3.238 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 30.224 ms/op
                 existUser·p1.00:   30.802 ms/op

Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  12.306 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292785
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12451 
    [ 2.500,  5.000) = 274399 
    [ 5.000,  7.500) = 5171 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     26.795 ms/op
     p(99.9990) =     30.650 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 8.743 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.010 ms/op
Iteration   1: 3.379 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  20.948 ms/op
                 getUser·p0.9999: 25.707 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.332 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  21.914 ms/op
                 getUser·p0.9999: 26.620 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 3.406 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  20.287 ms/op
                 getUser·p0.9999: 27.230 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284663
  mean =      3.372 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8021 
    [ 2.500,  5.000) = 270098 
    [ 5.000,  7.500) = 5566 
    [ 7.500, 10.000) = 645 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 126 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     20.316 ms/op
     p(99.9900) =     26.691 ms/op
     p(99.9990) =     27.751 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 10.817 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.013 ms/op
Iteration   1: 4.066 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  18.167 ms/op
                 listUser·p0.9999: 25.698 ms/op
                 listUser·p1.00:   27.951 ms/op

Iteration   2: 3.906 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 17.983 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 4.078 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 16.710 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239144
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 228915 
    [ 5.000,  7.500) = 7821 
    [ 7.500, 10.000) = 1494 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 257 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     26.263 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.298 ± 4.240  ops/ms
ClientPb.existUser                       thrpt       3   9.676 ± 1.019  ops/ms
ClientPb.getUser                         thrpt       3   9.452 ± 4.357  ops/ms
ClientPb.listUser                        thrpt       3   8.066 ± 1.327  ops/ms
ClientPb.createUser                       avgt       3   3.354 ± 1.748   ms/op
ClientPb.existUser                        avgt       3   3.301 ± 1.776   ms/op
ClientPb.getUser                          avgt       3   3.451 ± 2.164   ms/op
ClientPb.listUser                         avgt       3   3.963 ± 1.372   ms/op
ClientPb.createUser                     sample  282987   3.391 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.280           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.234           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.434           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.704           ms/op
ClientPb.existUser                      sample  292785   3.277 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.251           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.912           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.795           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.802           ms/op
ClientPb.getUser                        sample  284663   3.372 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.316           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.691           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  239144   4.015 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.231           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.302           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.035           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.951           ms/op
