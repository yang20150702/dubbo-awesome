# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 11.635 ops/ms
# Warmup Iteration   3: 11.917 ops/ms
Iteration   1: 12.288 ops/ms
Iteration   2: 12.414 ops/ms
Iteration   3: 12.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.331 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (12.288, 12.331, 12.414), stdev = 0.072
  CI (99.9%): [11.019, 13.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.393 ops/ms
# Warmup Iteration   2: 12.674 ops/ms
# Warmup Iteration   3: 12.630 ops/ms
Iteration   1: 12.750 ops/ms
Iteration   2: 12.678 ops/ms
Iteration   3: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.677 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (12.604, 12.677, 12.750), stdev = 0.073
  CI (99.9%): [11.350, 14.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.054 ops/ms
# Warmup Iteration   2: 11.940 ops/ms
# Warmup Iteration   3: 12.313 ops/ms
Iteration   1: 12.453 ops/ms
Iteration   2: 12.505 ops/ms
Iteration   3: 12.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.499 ±(99.9%) 0.784 ops/ms [Average]
  (min, avg, max) = (12.453, 12.499, 12.538), stdev = 0.043
  CI (99.9%): [11.714, 13.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.979 ops/ms
# Warmup Iteration   2: 10.183 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 10.303 ops/ms
Iteration   2: 10.284 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.325 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (10.284, 10.325, 10.388), stdev = 0.056
  CI (99.9%): [9.311, 11.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.084 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.615 ±(99.9%) 0.004 ms/op
Iteration   1: 2.606 ±(99.9%) 0.004 ms/op
Iteration   2: 2.578 ±(99.9%) 0.004 ms/op
Iteration   3: 2.562 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.582 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.562, 2.582, 2.606), stdev = 0.022
  CI (99.9%): [2.178, 2.987] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.493 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (2.479, 2.493, 2.517), stdev = 0.021
  CI (99.9%): [2.114, 2.872] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.548 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.545 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (2.541, 2.545, 2.548), stdev = 0.004
  CI (99.9%): [2.480, 2.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.865 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.005 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
Iteration   2: 3.076 ±(99.9%) 0.004 ms/op
Iteration   3: 3.091 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.066 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.030, 3.066, 3.091), stdev = 0.032
  CI (99.9%): [2.486, 3.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.322 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.687 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  11.728 ms/op
                 createUser·p0.9999: 13.943 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  10.371 ms/op
                 createUser·p0.9999: 13.920 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  9.581 ms/op
                 createUser·p0.9999: 11.616 ms/op
                 createUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375238
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 177599 
    [ 2.500,  3.750) = 191886 
    [ 3.750,  5.000) = 4589 
    [ 5.000,  6.250) = 634 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     13.770 ms/op
     p(99.9990) =     14.663 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.735 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 14.012 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  8.945 ms/op
                 existUser·p0.9999: 15.598 ms/op
                 existUser·p1.00:   16.531 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 12.861 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383359
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 185907 
    [ 2.500,  3.750) = 193355 
    [ 3.750,  5.000) = 3088 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.873 ms/op
     p(99.9900) =     14.118 ms/op
     p(99.9990) =     16.305 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  12.532 ms/op
                 getUser·p0.9999: 13.976 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  9.963 ms/op
                 getUser·p0.9999: 12.984 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 11.502 ms/op
                 getUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380936
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 186939 
    [ 2.500,  3.750) = 188426 
    [ 3.750,  5.000) = 4183 
    [ 5.000,  6.250) = 774 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      9.438 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.064 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.050 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.009 ms/op
Iteration   1: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.475 ms/op
                 listUser·p0.9999: 11.228 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.763 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.771 ms/op
                 listUser·p0.9999: 12.969 ms/op
                 listUser·p1.00:   13.320 ms/op

Iteration   3: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.331 ms/op
                 listUser·p0.9999: 12.324 ms/op
                 listUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312766
  mean =      3.067 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 81760 
    [ 2.500,  3.750) = 188798 
    [ 3.750,  5.000) = 34127 
    [ 5.000,  6.250) = 6504 
    [ 6.250,  7.500) = 759 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 230 
    [10.000, 11.250) = 167 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     12.272 ms/op
     p(99.9990) =     13.314 ms/op
     p(99.9999) =     13.402 ms/op
    p(100.0000) =     13.402 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.331 ± 1.312  ops/ms
ClientPb.existUser                       thrpt       3  12.677 ± 1.327  ops/ms
ClientPb.getUser                         thrpt       3  12.499 ± 0.784  ops/ms
ClientPb.listUser                        thrpt       3  10.325 ± 1.014  ops/ms
ClientPb.createUser                       avgt       3   2.582 ± 0.404   ms/op
ClientPb.existUser                        avgt       3   2.493 ± 0.379   ms/op
ClientPb.getUser                          avgt       3   2.545 ± 0.065   ms/op
ClientPb.listUser                         avgt       3   3.066 ± 0.580   ms/op
ClientPb.createUser                     sample  375238   2.556 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.585           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.770           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.106           ms/op
ClientPb.existUser                      sample  383359   2.502 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.869           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.873           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.118           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.531           ms/op
ClientPb.getUser                        sample  380936   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.784           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.648           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.107           ms/op
ClientPb.listUser                       sample  312766   3.067 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.765           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.272           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.402           ms/op
