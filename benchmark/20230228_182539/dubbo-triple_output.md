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
# Warmup Iteration   2: 2.047 ops/ms
# Warmup Iteration   3: 4.100 ops/ms
Iteration   1: 4.951 ops/ms
Iteration   2: 5.190 ops/ms
Iteration   3: 5.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.121 ±(99.9%) 2.699 ops/ms [Average]
  (min, avg, max) = (4.951, 5.121, 5.221), stdev = 0.148
  CI (99.9%): [2.422, 7.819] (assumes normal distribution)


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
# Warmup Iteration   1: 1.412 ops/ms
# Warmup Iteration   2: 3.593 ops/ms
# Warmup Iteration   3: 5.447 ops/ms
Iteration   1: 5.446 ops/ms
Iteration   2: 5.624 ops/ms
Iteration   3: 5.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.392 ±(99.9%) 4.796 ops/ms [Average]
  (min, avg, max) = (5.107, 5.392, 5.624), stdev = 0.263
  CI (99.9%): [0.596, 10.188] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.354 ops/ms
# Warmup Iteration   2: 4.050 ops/ms
# Warmup Iteration   3: 4.934 ops/ms
Iteration   1: 4.989 ops/ms
Iteration   2: 5.114 ops/ms
Iteration   3: 5.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.112 ±(99.9%) 2.215 ops/ms [Average]
  (min, avg, max) = (4.989, 5.112, 5.232), stdev = 0.121
  CI (99.9%): [2.896, 7.327] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.363 ops/ms
# Warmup Iteration   2: 3.392 ops/ms
# Warmup Iteration   3: 4.450 ops/ms
Iteration   1: 4.636 ops/ms
Iteration   2: 4.122 ops/ms
Iteration   3: 4.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.483 ±(99.9%) 5.721 ops/ms [Average]
  (min, avg, max) = (4.122, 4.483, 4.690), stdev = 0.314
  CI (99.9%): [≈ 0, 10.204] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.042 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 7.939 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.491 ±(99.9%) 0.011 ms/op
Iteration   1: 6.061 ±(99.9%) 0.008 ms/op
Iteration   2: 5.963 ±(99.9%) 0.013 ms/op
Iteration   3: 6.004 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.009 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (5.963, 6.009, 6.061), stdev = 0.049
  CI (99.9%): [5.113, 6.905] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 21.725 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.578 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.830 ±(99.9%) 0.008 ms/op
Iteration   1: 5.448 ±(99.9%) 0.011 ms/op
Iteration   2: 5.429 ±(99.9%) 0.018 ms/op
Iteration   3: 5.475 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.451 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (5.429, 5.451, 5.475), stdev = 0.023
  CI (99.9%): [5.030, 5.872] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.194 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.212 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.971 ±(99.9%) 0.010 ms/op
Iteration   1: 6.111 ±(99.9%) 0.009 ms/op
Iteration   2: 5.844 ±(99.9%) 0.015 ms/op
Iteration   3: 5.818 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.924 ±(99.9%) 2.957 ms/op [Average]
  (min, avg, max) = (5.818, 5.924, 6.111), stdev = 0.162
  CI (99.9%): [2.967, 8.881] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.779 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 9.126 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 7.065 ±(99.9%) 0.019 ms/op
Iteration   1: 6.777 ±(99.9%) 0.012 ms/op
Iteration   2: 6.588 ±(99.9%) 0.022 ms/op
Iteration   3: 7.148 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.838 ±(99.9%) 5.192 ms/op [Average]
  (min, avg, max) = (6.588, 6.838, 7.148), stdev = 0.285
  CI (99.9%): [1.646, 12.030] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.689 ±(99.9%) 0.402 ms/op
# Warmup Iteration   2: 7.557 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.308 ±(99.9%) 0.034 ms/op
Iteration   1: 5.912 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   5.558 ms/op
                 createUser·p0.90:   7.422 ms/op
                 createUser·p0.95:   8.602 ms/op
                 createUser·p0.99:   11.637 ms/op
                 createUser·p0.999:  18.282 ms/op
                 createUser·p0.9999: 45.914 ms/op
                 createUser·p1.00:   47.972 ms/op

Iteration   2: 6.063 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   5.628 ms/op
                 createUser·p0.90:   7.774 ms/op
                 createUser·p0.95:   9.306 ms/op
                 createUser·p0.99:   13.138 ms/op
                 createUser·p0.999:  30.765 ms/op
                 createUser·p0.9999: 33.278 ms/op
                 createUser·p1.00:   36.766 ms/op

Iteration   3: 5.788 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   7.160 ms/op
                 createUser·p0.95:   8.176 ms/op
                 createUser·p0.99:   11.747 ms/op
                 createUser·p0.999:  31.078 ms/op
                 createUser·p0.9999: 35.258 ms/op
                 createUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161921
  mean =      5.919 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 37463 
    [ 5.000, 10.000) = 120250 
    [10.000, 15.000) = 3525 
    [15.000, 20.000) = 430 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 40 
    [30.000, 35.000) = 125 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     30.278 ms/op
     p(99.9900) =     44.355 ms/op
     p(99.9990) =     47.688 ms/op
     p(99.9999) =     47.972 ms/op
    p(100.0000) =     47.972 ms/op


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
# Warmup Iteration   1: 18.696 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.593 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.539 ±(99.9%) 0.022 ms/op
Iteration   1: 5.501 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   7.021 ms/op
                 existUser·p0.95:   8.167 ms/op
                 existUser·p0.99:   11.239 ms/op
                 existUser·p0.999:  27.550 ms/op
                 existUser·p0.9999: 30.874 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   2: 5.660 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.091 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   7.356 ms/op
                 existUser·p0.95:   8.667 ms/op
                 existUser·p0.99:   12.177 ms/op
                 existUser·p0.999:  18.974 ms/op
                 existUser·p0.9999: 29.312 ms/op
                 existUser·p1.00:   30.310 ms/op

Iteration   3: 5.415 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.717 ms/op
                 existUser·p0.95:   7.725 ms/op
                 existUser·p0.99:   11.796 ms/op
                 existUser·p0.999:  27.589 ms/op
                 existUser·p0.9999: 31.002 ms/op
                 existUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173632
  mean =      5.524 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 74435 
    [ 5.000,  7.500) = 86344 
    [ 7.500, 10.000) = 9099 
    [10.000, 12.500) = 2360 
    [12.500, 15.000) = 837 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      7.021 ms/op
     p(95.0000) =      8.233 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     21.770 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     31.740 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 18.911 ±(99.9%) 0.321 ms/op
# Warmup Iteration   2: 7.129 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.765 ±(99.9%) 0.024 ms/op
Iteration   1: 6.158 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.060 ms/op
                 getUser·p0.50:   5.603 ms/op
                 getUser·p0.90:   8.184 ms/op
                 getUser·p0.95:   10.125 ms/op
                 getUser·p0.99:   15.069 ms/op
                 getUser·p0.999:  24.000 ms/op
                 getUser·p0.9999: 29.329 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   2: 6.095 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   5.636 ms/op
                 getUser·p0.90:   8.028 ms/op
                 getUser·p0.95:   9.699 ms/op
                 getUser·p0.99:   12.672 ms/op
                 getUser·p0.999:  28.165 ms/op
                 getUser·p0.9999: 38.160 ms/op
                 getUser·p1.00:   42.205 ms/op

Iteration   3: 5.991 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.495 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.660 ms/op
                 getUser·p0.95:   9.388 ms/op
                 getUser·p0.99:   13.421 ms/op
                 getUser·p0.999:  30.088 ms/op
                 getUser·p0.9999: 33.117 ms/op
                 getUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 157776
  mean =      6.081 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 36528 
    [ 5.000, 10.000) = 114152 
    [10.000, 15.000) = 6066 
    [15.000, 20.000) = 778 
    [20.000, 25.000) = 78 
    [25.000, 30.000) = 85 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      7.954 ms/op
     p(95.0000) =      9.732 ms/op
     p(99.0000) =     13.713 ms/op
     p(99.9000) =     27.154 ms/op
     p(99.9900) =     36.831 ms/op
     p(99.9990) =     41.978 ms/op
     p(99.9999) =     42.205 ms/op
    p(100.0000) =     42.205 ms/op


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
# Warmup Iteration   1: 25.365 ±(99.9%) 0.768 ms/op
# Warmup Iteration   2: 9.532 ±(99.9%) 0.084 ms/op
# Warmup Iteration   3: 7.569 ±(99.9%) 0.042 ms/op
Iteration   1: 6.803 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   8.815 ms/op
                 listUser·p0.95:   10.636 ms/op
                 listUser·p0.99:   14.025 ms/op
                 listUser·p0.999:  31.776 ms/op
                 listUser·p0.9999: 42.664 ms/op
                 listUser·p1.00:   44.171 ms/op

Iteration   2: 7.016 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   6.365 ms/op
                 listUser·p0.90:   9.519 ms/op
                 listUser·p0.95:   11.158 ms/op
                 listUser·p0.99:   14.959 ms/op
                 listUser·p0.999:  31.396 ms/op
                 listUser·p0.9999: 34.959 ms/op
                 listUser·p1.00:   40.763 ms/op

Iteration   3: 6.990 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   9.159 ms/op
                 listUser·p0.95:   10.486 ms/op
                 listUser·p0.99:   14.369 ms/op
                 listUser·p0.999:  31.934 ms/op
                 listUser·p0.9999: 37.187 ms/op
                 listUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138398
  mean =      6.935 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3427 
    [ 5.000, 10.000) = 124958 
    [10.000, 15.000) = 8936 
    [15.000, 20.000) = 716 
    [20.000, 25.000) = 72 
    [25.000, 30.000) = 81 
    [30.000, 35.000) = 149 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      6.324 ms/op
     p(90.0000) =      9.175 ms/op
     p(95.0000) =     10.764 ms/op
     p(99.0000) =     14.500 ms/op
     p(99.9000) =     31.680 ms/op
     p(99.9900) =     41.571 ms/op
     p(99.9990) =     43.945 ms/op
     p(99.9999) =     44.171 ms/op
    p(100.0000) =     44.171 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.121 ± 2.699  ops/ms
ClientPb.existUser                       thrpt       3   5.392 ± 4.796  ops/ms
ClientPb.getUser                         thrpt       3   5.112 ± 2.215  ops/ms
ClientPb.listUser                        thrpt       3   4.483 ± 5.721  ops/ms
ClientPb.createUser                       avgt       3   6.009 ± 0.896   ms/op
ClientPb.existUser                        avgt       3   5.451 ± 0.421   ms/op
ClientPb.getUser                          avgt       3   5.924 ± 2.957   ms/op
ClientPb.listUser                         avgt       3   6.838 ± 5.192   ms/op
ClientPb.createUser                     sample  161921   5.919 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.793           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.430           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.733           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.255           ms/op
ClientPb.createUser:createUser·p0.999   sample          30.278           ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.355           ms/op
ClientPb.createUser:createUser·p1.00    sample          47.972           ms/op
ClientPb.existUser                      sample  173632   5.524 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.546           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.021           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.233           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.747           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.770           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.769           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.982           ms/op
ClientPb.getUser                        sample  157776   6.081 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.495           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.587           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.954           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.732           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.713           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.154           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.831           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.205           ms/op
ClientPb.listUser                       sample  138398   6.935 ± 0.019   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.395           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.324           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.764           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.500           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.571           ms/op
ClientPb.listUser:listUser·p1.00        sample          44.171           ms/op
