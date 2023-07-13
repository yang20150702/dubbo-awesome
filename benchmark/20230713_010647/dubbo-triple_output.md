# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.840 ops/ms
# Warmup Iteration   2: 1.822 ops/ms
# Warmup Iteration   3: 4.114 ops/ms
Iteration   1: 5.378 ops/ms
Iteration   2: 5.640 ops/ms
Iteration   3: 5.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.609 ±(99.9%) 3.949 ops/ms [Average]
  (min, avg, max) = (5.378, 5.609, 5.808), stdev = 0.216
  CI (99.9%): [1.660, 9.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.386 ops/ms
# Warmup Iteration   2: 4.109 ops/ms
# Warmup Iteration   3: 5.404 ops/ms
Iteration   1: 5.780 ops/ms
Iteration   2: 5.815 ops/ms
Iteration   3: 6.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.886 ±(99.9%) 2.812 ops/ms [Average]
  (min, avg, max) = (5.780, 5.886, 6.063), stdev = 0.154
  CI (99.9%): [3.074, 8.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.322 ops/ms
# Warmup Iteration   2: 3.840 ops/ms
# Warmup Iteration   3: 5.428 ops/ms
Iteration   1: 5.409 ops/ms
Iteration   2: 5.451 ops/ms
Iteration   3: 5.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.330 ±(99.9%) 3.179 ops/ms [Average]
  (min, avg, max) = (5.130, 5.330, 5.451), stdev = 0.174
  CI (99.9%): [2.151, 8.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.287 ops/ms
# Warmup Iteration   2: 3.602 ops/ms
# Warmup Iteration   3: 4.567 ops/ms
Iteration   1: 4.530 ops/ms
Iteration   2: 4.720 ops/ms
Iteration   3: 4.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.642 ±(99.9%) 1.816 ops/ms [Average]
  (min, avg, max) = (4.530, 4.642, 4.720), stdev = 0.100
  CI (99.9%): [2.826, 6.457] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 21.893 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.790 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.247 ±(99.9%) 0.010 ms/op
Iteration   1: 6.352 ±(99.9%) 0.014 ms/op
Iteration   2: 6.106 ±(99.9%) 0.009 ms/op
Iteration   3: 5.992 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.150 ±(99.9%) 3.356 ms/op [Average]
  (min, avg, max) = (5.992, 6.150, 6.352), stdev = 0.184
  CI (99.9%): [2.794, 9.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 22.423 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 7.849 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.753 ±(99.9%) 0.007 ms/op
Iteration   1: 5.826 ±(99.9%) 0.008 ms/op
Iteration   2: 5.503 ±(99.9%) 0.011 ms/op
Iteration   3: 5.504 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.611 ±(99.9%) 3.398 ms/op [Average]
  (min, avg, max) = (5.503, 5.611, 5.826), stdev = 0.186
  CI (99.9%): [2.213, 9.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 20.141 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.798 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.006 ms/op
Iteration   1: 5.630 ±(99.9%) 0.009 ms/op
Iteration   2: 5.763 ±(99.9%) 0.014 ms/op
Iteration   3: 5.614 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.669 ±(99.9%) 1.486 ms/op [Average]
  (min, avg, max) = (5.614, 5.669, 5.763), stdev = 0.081
  CI (99.9%): [4.183, 7.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.421 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 8.265 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.639 ±(99.9%) 0.014 ms/op
Iteration   1: 6.581 ±(99.9%) 0.017 ms/op
Iteration   2: 6.793 ±(99.9%) 0.008 ms/op
Iteration   3: 6.607 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.660 ±(99.9%) 2.112 ms/op [Average]
  (min, avg, max) = (6.581, 6.660, 6.793), stdev = 0.116
  CI (99.9%): [4.548, 8.772] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.519 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 7.107 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.266 ±(99.9%) 0.030 ms/op
Iteration   1: 5.444 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   7.758 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  13.562 ms/op
                 createUser·p0.9999: 29.360 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   2: 5.476 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.676 ms/op
                 createUser·p0.95:   7.494 ms/op
                 createUser·p0.99:   10.437 ms/op
                 createUser·p0.999:  15.573 ms/op
                 createUser·p0.9999: 28.639 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   3: 5.716 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   8.602 ms/op
                 createUser·p0.99:   11.469 ms/op
                 createUser·p0.999:  25.803 ms/op
                 createUser·p0.9999: 30.324 ms/op
                 createUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173170
  mean =      5.543 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 65344 
    [ 5.000,  7.500) = 96518 
    [ 7.500, 10.000) = 8623 
    [10.000, 12.500) = 1995 
    [12.500, 15.000) = 389 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      7.971 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     29.907 ms/op
     p(99.9990) =     30.514 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.701 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 7.850 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 5.556 ±(99.9%) 0.022 ms/op
Iteration   1: 5.394 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.464 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.717 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  15.269 ms/op
                 existUser·p0.9999: 28.282 ms/op
                 existUser·p1.00:   29.688 ms/op

Iteration   2: 5.479 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   7.012 ms/op
                 existUser·p0.95:   8.061 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  24.117 ms/op
                 existUser·p0.9999: 29.693 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 5.146 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.300 ms/op
                 existUser·p0.95:   7.307 ms/op
                 existUser·p0.99:   9.922 ms/op
                 existUser·p0.999:  25.569 ms/op
                 existUser·p0.9999: 28.534 ms/op
                 existUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179734
  mean =      5.336 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 89711 
    [ 5.000,  7.500) = 79669 
    [ 7.500, 10.000) = 8295 
    [10.000, 12.500) = 1418 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     17.179 ms/op
     p(99.9900) =     28.970 ms/op
     p(99.9990) =     30.029 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.194 ±(99.9%) 0.323 ms/op
# Warmup Iteration   2: 7.193 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.612 ±(99.9%) 0.022 ms/op
Iteration   1: 5.468 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   7.758 ms/op
                 getUser·p0.99:   10.584 ms/op
                 getUser·p0.999:  22.138 ms/op
                 getUser·p0.9999: 25.269 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 5.439 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.676 ms/op
                 getUser·p0.95:   7.881 ms/op
                 getUser·p0.99:   10.715 ms/op
                 getUser·p0.999:  26.378 ms/op
                 getUser·p0.9999: 31.596 ms/op
                 getUser·p1.00:   36.897 ms/op

Iteration   3: 5.410 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.570 ms/op
                 getUser·p0.95:   7.643 ms/op
                 getUser·p0.99:   9.961 ms/op
                 getUser·p0.999:  15.745 ms/op
                 getUser·p0.9999: 31.397 ms/op
                 getUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176455
  mean =      5.439 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 72693 
    [ 5.000,  7.500) = 93684 
    [ 7.500, 10.000) = 7887 
    [10.000, 12.500) = 1473 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     22.235 ms/op
     p(99.9900) =     30.586 ms/op
     p(99.9990) =     36.847 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.961 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 8.052 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.634 ±(99.9%) 0.029 ms/op
Iteration   1: 6.438 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   8.192 ms/op
                 listUser·p0.95:   9.601 ms/op
                 listUser·p0.99:   13.222 ms/op
                 listUser·p0.999:  26.236 ms/op
                 listUser·p0.9999: 30.056 ms/op
                 listUser·p1.00:   31.261 ms/op

Iteration   2: 6.580 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.200 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   12.321 ms/op
                 listUser·p0.999:  30.975 ms/op
                 listUser·p0.9999: 34.537 ms/op
                 listUser·p1.00:   35.521 ms/op

Iteration   3: 6.421 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.531 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.881 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.342 ms/op
                 listUser·p0.999:  28.349 ms/op
                 listUser·p0.9999: 32.903 ms/op
                 listUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148008
  mean =      6.479 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 6732 
    [ 5.000,  7.500) = 119382 
    [ 7.500, 10.000) = 16738 
    [10.000, 12.500) = 3504 
    [12.500, 15.000) = 918 
    [15.000, 17.500) = 294 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 78 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      6.038 ms/op
     p(90.0000) =      8.094 ms/op
     p(95.0000) =      9.404 ms/op
     p(99.0000) =     12.829 ms/op
     p(99.9000) =     28.901 ms/op
     p(99.9900) =     32.984 ms/op
     p(99.9990) =     35.458 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.609 ± 3.949  ops/ms
ClientPb.existUser                       thrpt       3   5.886 ± 2.812  ops/ms
ClientPb.getUser                         thrpt       3   5.330 ± 3.179  ops/ms
ClientPb.listUser                        thrpt       3   4.642 ± 1.816  ops/ms
ClientPb.createUser                       avgt       3   6.150 ± 3.356   ms/op
ClientPb.existUser                        avgt       3   5.611 ± 3.398   ms/op
ClientPb.getUser                          avgt       3   5.669 ± 1.486   ms/op
ClientPb.listUser                         avgt       3   6.660 ± 2.112   ms/op
ClientPb.createUser                     sample  173170   5.543 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.814           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.186           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.971           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.830           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.876           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.907           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.802           ms/op
ClientPb.existUser                      sample  179734   5.336 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.464           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.725           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.179           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.081           ms/op
ClientPb.getUser                        sample  176455   5.439 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.688           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.627           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.758           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.355           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.235           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.586           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.897           ms/op
ClientPb.listUser                       sample  148008   6.479 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.531           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.038           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.404           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.829           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.901           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.984           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.521           ms/op
