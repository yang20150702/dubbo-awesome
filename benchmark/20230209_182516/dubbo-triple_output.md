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
# Warmup Iteration   1: 0.945 ops/ms
# Warmup Iteration   2: 2.460 ops/ms
# Warmup Iteration   3: 4.902 ops/ms
Iteration   1: 5.157 ops/ms
Iteration   2: 5.482 ops/ms
Iteration   3: 5.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.476 ±(99.9%) 5.767 ops/ms [Average]
  (min, avg, max) = (5.157, 5.476, 5.789), stdev = 0.316
  CI (99.9%): [≈ 0, 11.242] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.527 ops/ms
# Warmup Iteration   2: 4.545 ops/ms
# Warmup Iteration   3: 5.805 ops/ms
Iteration   1: 5.943 ops/ms
Iteration   2: 5.917 ops/ms
Iteration   3: 6.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.028 ±(99.9%) 3.112 ops/ms [Average]
  (min, avg, max) = (5.917, 6.028, 6.225), stdev = 0.171
  CI (99.9%): [2.917, 9.140] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.604 ops/ms
# Warmup Iteration   2: 4.513 ops/ms
# Warmup Iteration   3: 5.509 ops/ms
Iteration   1: 5.752 ops/ms
Iteration   2: 5.620 ops/ms
Iteration   3: 5.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.728 ±(99.9%) 1.796 ops/ms [Average]
  (min, avg, max) = (5.620, 5.728, 5.813), stdev = 0.098
  CI (99.9%): [3.933, 7.524] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 4.030 ops/ms
# Warmup Iteration   3: 5.075 ops/ms
Iteration   1: 4.986 ops/ms
Iteration   2: 4.634 ops/ms
Iteration   3: 4.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.838 ±(99.9%) 3.329 ops/ms [Average]
  (min, avg, max) = (4.634, 4.838, 4.986), stdev = 0.182
  CI (99.9%): [1.509, 8.168] (assumes normal distribution)


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
# Warmup Iteration   1: 16.813 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.516 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.720 ±(99.9%) 0.016 ms/op
Iteration   1: 5.324 ±(99.9%) 0.019 ms/op
Iteration   2: 5.429 ±(99.9%) 0.012 ms/op
Iteration   3: 5.469 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.407 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (5.324, 5.407, 5.469), stdev = 0.075
  CI (99.9%): [4.042, 6.772] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 16.791 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.284 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.394 ±(99.9%) 0.013 ms/op
Iteration   1: 5.366 ±(99.9%) 0.013 ms/op
Iteration   2: 5.267 ±(99.9%) 0.015 ms/op
Iteration   3: 5.283 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.305 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (5.267, 5.305, 5.366), stdev = 0.053
  CI (99.9%): [4.341, 6.270] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 17.609 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.618 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.734 ±(99.9%) 0.007 ms/op
Iteration   1: 5.337 ±(99.9%) 0.019 ms/op
Iteration   2: 5.493 ±(99.9%) 0.018 ms/op
Iteration   3: 5.499 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.443 ±(99.9%) 1.678 ms/op [Average]
  (min, avg, max) = (5.337, 5.443, 5.499), stdev = 0.092
  CI (99.9%): [3.766, 7.121] (assumes normal distribution)


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
# Warmup Iteration   1: 19.224 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 8.316 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.598 ±(99.9%) 0.012 ms/op
Iteration   1: 6.520 ±(99.9%) 0.016 ms/op
Iteration   2: 6.657 ±(99.9%) 0.014 ms/op
Iteration   3: 6.455 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.544 ±(99.9%) 1.880 ms/op [Average]
  (min, avg, max) = (6.455, 6.544, 6.657), stdev = 0.103
  CI (99.9%): [4.664, 8.423] (assumes normal distribution)


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
# Warmup Iteration   1: 18.445 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 7.364 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.920 ±(99.9%) 0.028 ms/op
Iteration   1: 5.666 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   7.897 ms/op
                 createUser·p0.99:   10.469 ms/op
                 createUser·p0.999:  25.526 ms/op
                 createUser·p0.9999: 28.410 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   2: 5.496 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.250 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  25.981 ms/op
                 createUser·p0.9999: 28.940 ms/op
                 createUser·p1.00:   29.983 ms/op

Iteration   3: 5.418 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.441 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   6.947 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  26.410 ms/op
                 createUser·p0.9999: 29.688 ms/op
                 createUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173621
  mean =      5.525 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 60777 
    [ 5.000,  7.500) = 104989 
    [ 7.500, 10.000) = 6161 
    [10.000, 12.500) = 1085 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     25.834 ms/op
     p(99.9900) =     29.307 ms/op
     p(99.9990) =     30.076 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 16.742 ±(99.9%) 0.320 ms/op
# Warmup Iteration   2: 6.264 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.355 ±(99.9%) 0.016 ms/op
Iteration   1: 5.299 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.974 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  23.609 ms/op
                 existUser·p0.9999: 30.308 ms/op
                 existUser·p1.00:   30.966 ms/op

Iteration   2: 5.268 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.400 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   7.733 ms/op
                 existUser·p0.99:   10.387 ms/op
                 existUser·p0.999:  17.334 ms/op
                 existUser·p0.9999: 28.408 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   3: 5.257 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.253 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  27.697 ms/op
                 existUser·p0.9999: 30.424 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181780
  mean =      5.274 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 97353 
    [ 5.000,  7.500) = 75309 
    [ 7.500, 10.000) = 7205 
    [10.000, 12.500) = 1222 
    [12.500, 15.000) = 368 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.076 ms/op
     p(99.9000) =     19.897 ms/op
     p(99.9900) =     30.042 ms/op
     p(99.9990) =     31.988 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 18.430 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.796 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.566 ±(99.9%) 0.018 ms/op
Iteration   1: 5.418 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.970 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.300 ms/op
                 getUser·p0.95:   7.373 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  23.822 ms/op
                 getUser·p0.9999: 27.863 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   2: 5.414 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.859 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.447 ms/op
                 getUser·p0.95:   7.258 ms/op
                 getUser·p0.99:   9.404 ms/op
                 getUser·p0.999:  27.618 ms/op
                 getUser·p0.9999: 36.307 ms/op
                 getUser·p1.00:   36.372 ms/op

Iteration   3: 5.588 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.736 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   6.439 ms/op
                 getUser·p0.95:   7.479 ms/op
                 getUser·p0.99:   11.633 ms/op
                 getUser·p0.999:  26.912 ms/op
                 getUser·p0.9999: 32.997 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175380
  mean =      5.472 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 64191 
    [ 5.000,  7.500) = 103034 
    [ 7.500, 10.000) = 5973 
    [10.000, 12.500) = 1370 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.736 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     25.841 ms/op
     p(99.9900) =     35.430 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 19.213 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.789 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.545 ±(99.9%) 0.023 ms/op
Iteration   1: 6.126 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   6.881 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   11.190 ms/op
                 listUser·p0.999:  26.241 ms/op
                 listUser·p0.9999: 32.590 ms/op
                 listUser·p1.00:   33.489 ms/op

Iteration   2: 6.450 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.596 ms/op
                 listUser·p0.50:   6.218 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.820 ms/op
                 listUser·p0.999:  28.508 ms/op
                 listUser·p0.9999: 32.474 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   3: 6.255 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.357 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  24.142 ms/op
                 listUser·p0.9999: 30.164 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152979
  mean =      6.274 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 4878 
    [ 5.000,  7.500) = 135637 
    [ 7.500, 10.000) = 9444 
    [10.000, 12.500) = 1981 
    [12.500, 15.000) = 536 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      5.956 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     26.444 ms/op
     p(99.9900) =     32.028 ms/op
     p(99.9990) =     33.263 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.476 ± 5.767  ops/ms
ClientPb.existUser                       thrpt       3   6.028 ± 3.112  ops/ms
ClientPb.getUser                         thrpt       3   5.728 ± 1.796  ops/ms
ClientPb.listUser                        thrpt       3   4.838 ± 3.329  ops/ms
ClientPb.createUser                       avgt       3   5.407 ± 1.365   ms/op
ClientPb.existUser                        avgt       3   5.305 ± 0.964   ms/op
ClientPb.getUser                          avgt       3   5.443 ± 1.678   ms/op
ClientPb.listUser                         avgt       3   6.544 ± 1.880   ms/op
ClientPb.createUser                     sample  173621   5.525 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.365           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.945           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.834           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.307           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.245           ms/op
ClientPb.existUser                      sample  181780   5.274 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.974           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.504           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.076           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.897           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.014           ms/op
ClientPb.getUser                        sample  175380   5.472 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.736           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.519           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.841           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.430           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.372           ms/op
ClientPb.listUser                       sample  152979   6.274 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.596           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.956           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.354           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.444           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.028           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.489           ms/op
