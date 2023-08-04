# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.245 ops/ms
# Warmup Iteration   2: 2.375 ops/ms
# Warmup Iteration   3: 4.980 ops/ms
Iteration   1: 5.491 ops/ms
Iteration   2: 5.783 ops/ms
Iteration   3: 5.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.597 ±(99.9%) 2.952 ops/ms [Average]
  (min, avg, max) = (5.491, 5.597, 5.783), stdev = 0.162
  CI (99.9%): [2.645, 8.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.583 ops/ms
# Warmup Iteration   2: 4.605 ops/ms
# Warmup Iteration   3: 5.974 ops/ms
Iteration   1: 6.118 ops/ms
Iteration   2: 6.059 ops/ms
Iteration   3: 6.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.106 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (6.059, 6.106, 6.142), stdev = 0.043
  CI (99.9%): [5.325, 6.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 3.988 ops/ms
# Warmup Iteration   3: 5.774 ops/ms
Iteration   1: 5.681 ops/ms
Iteration   2: 5.610 ops/ms
Iteration   3: 5.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.756 ±(99.9%) 3.546 ops/ms [Average]
  (min, avg, max) = (5.610, 5.756, 5.976), stdev = 0.194
  CI (99.9%): [2.210, 9.302] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.561 ops/ms
# Warmup Iteration   2: 4.385 ops/ms
# Warmup Iteration   3: 4.902 ops/ms
Iteration   1: 4.846 ops/ms
Iteration   2: 4.909 ops/ms
Iteration   3: 4.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.900 ±(99.9%) 0.911 ops/ms [Average]
  (min, avg, max) = (4.846, 4.900, 4.945), stdev = 0.050
  CI (99.9%): [3.989, 5.811] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 20.006 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.609 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.940 ±(99.9%) 0.011 ms/op
Iteration   1: 5.676 ±(99.9%) 0.013 ms/op
Iteration   2: 5.871 ±(99.9%) 0.015 ms/op
Iteration   3: 5.872 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.807 ±(99.9%) 2.061 ms/op [Average]
  (min, avg, max) = (5.676, 5.807, 5.872), stdev = 0.113
  CI (99.9%): [3.745, 7.868] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 17.442 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.378 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.864 ±(99.9%) 0.008 ms/op
Iteration   1: 5.419 ±(99.9%) 0.012 ms/op
Iteration   2: 5.457 ±(99.9%) 0.009 ms/op
Iteration   3: 5.276 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.384 ±(99.9%) 1.745 ms/op [Average]
  (min, avg, max) = (5.276, 5.384, 5.457), stdev = 0.096
  CI (99.9%): [3.639, 7.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 18.153 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.560 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.507 ±(99.9%) 0.021 ms/op
Iteration   1: 5.686 ±(99.9%) 0.006 ms/op
Iteration   2: 5.915 ±(99.9%) 0.014 ms/op
Iteration   3: 5.681 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.760 ±(99.9%) 2.440 ms/op [Average]
  (min, avg, max) = (5.681, 5.760, 5.915), stdev = 0.134
  CI (99.9%): [3.320, 8.201] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.612 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.857 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.571 ±(99.9%) 0.012 ms/op
Iteration   1: 6.524 ±(99.9%) 0.014 ms/op
Iteration   2: 6.348 ±(99.9%) 0.016 ms/op
Iteration   3: 6.300 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.390 ±(99.9%) 2.151 ms/op [Average]
  (min, avg, max) = (6.300, 6.390, 6.524), stdev = 0.118
  CI (99.9%): [4.240, 8.541] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 17.308 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 6.448 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.049 ±(99.9%) 0.027 ms/op
Iteration   1: 5.470 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.130 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.782 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  21.711 ms/op
                 createUser·p0.9999: 25.854 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   2: 5.736 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.348 ms/op
                 createUser·p0.95:   8.470 ms/op
                 createUser·p0.99:   10.823 ms/op
                 createUser·p0.999:  26.878 ms/op
                 createUser·p0.9999: 30.380 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   3: 5.743 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.119 ms/op
                 createUser·p0.95:   7.873 ms/op
                 createUser·p0.99:   10.486 ms/op
                 createUser·p0.999:  14.778 ms/op
                 createUser·p0.9999: 34.762 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169881
  mean =      5.647 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 57747 
    [ 5.000,  7.500) = 99678 
    [ 7.500, 10.000) = 10089 
    [10.000, 12.500) = 1711 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.130 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.127 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     32.867 ms/op
     p(99.9990) =     35.095 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.957 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 6.354 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.601 ±(99.9%) 0.022 ms/op
Iteration   1: 5.485 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   6.734 ms/op
                 existUser·p0.95:   7.766 ms/op
                 existUser·p0.99:   10.914 ms/op
                 existUser·p0.999:  24.276 ms/op
                 existUser·p0.9999: 27.995 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 5.627 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.318 ms/op
                 existUser·p0.50:   5.382 ms/op
                 existUser·p0.90:   7.102 ms/op
                 existUser·p0.95:   7.963 ms/op
                 existUser·p0.99:   10.961 ms/op
                 existUser·p0.999:  16.031 ms/op
                 existUser·p0.9999: 29.049 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   3: 5.238 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.927 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.594 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  24.674 ms/op
                 existUser·p0.9999: 30.206 ms/op
                 existUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176143
  mean =      5.445 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 78250 
    [ 5.000,  7.500) = 86925 
    [ 7.500, 10.000) = 8258 
    [10.000, 12.500) = 1851 
    [12.500, 15.000) = 482 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      7.781 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     19.132 ms/op
     p(99.9900) =     28.947 ms/op
     p(99.9990) =     31.531 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.861 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.409 ±(99.9%) 0.022 ms/op
Iteration   1: 5.838 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   7.881 ms/op
                 getUser·p0.95:   9.454 ms/op
                 getUser·p0.99:   13.582 ms/op
                 getUser·p0.999:  22.465 ms/op
                 getUser·p0.9999: 26.284 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 5.612 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.712 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   11.567 ms/op
                 getUser·p0.999:  25.426 ms/op
                 getUser·p0.9999: 30.953 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   3: 5.606 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.814 ms/op
                 getUser·p0.50:   5.448 ms/op
                 getUser·p0.90:   6.914 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  31.423 ms/op
                 getUser·p0.9999: 35.422 ms/op
                 getUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168846
  mean =      5.683 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 60951 
    [ 5.000,  7.500) = 93848 
    [ 7.500, 10.000) = 10012 
    [10.000, 12.500) = 2551 
    [12.500, 15.000) = 884 
    [15.000, 17.500) = 238 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.241 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     34.321 ms/op
     p(99.9990) =     36.593 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.609 ±(99.9%) 0.345 ms/op
# Warmup Iteration   2: 7.910 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.470 ±(99.9%) 0.026 ms/op
Iteration   1: 6.512 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.178 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.036 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   13.173 ms/op
                 listUser·p0.999:  24.765 ms/op
                 listUser·p0.9999: 28.511 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   2: 6.464 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.871 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   12.714 ms/op
                 listUser·p0.999:  26.313 ms/op
                 listUser·p0.9999: 29.364 ms/op
                 listUser·p1.00:   31.523 ms/op

Iteration   3: 6.587 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.990 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   8.282 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   13.224 ms/op
                 listUser·p0.999:  23.020 ms/op
                 listUser·p0.9999: 29.087 ms/op
                 listUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147180
  mean =      6.521 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 9031 
    [ 5.000,  7.500) = 115609 
    [ 7.500, 10.000) = 17510 
    [10.000, 12.500) = 3212 
    [12.500, 15.000) = 1245 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.871 ms/op
     p(50.0000) =      6.185 ms/op
     p(90.0000) =      8.086 ms/op
     p(95.0000) =      9.273 ms/op
     p(99.0000) =     12.976 ms/op
     p(99.9000) =     24.963 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     31.923 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.597 ± 2.952  ops/ms
ClientPb.existUser                       thrpt       3   6.106 ± 0.781  ops/ms
ClientPb.getUser                         thrpt       3   5.756 ± 3.546  ops/ms
ClientPb.listUser                        thrpt       3   4.900 ± 0.911  ops/ms
ClientPb.createUser                       avgt       3   5.807 ± 2.061   ms/op
ClientPb.existUser                        avgt       3   5.384 ± 1.745   ms/op
ClientPb.getUser                          avgt       3   5.760 ± 2.440   ms/op
ClientPb.listUser                         avgt       3   6.390 ± 2.151   ms/op
ClientPb.createUser                     sample  169881   5.647 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.127           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.995           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.535           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.367           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.867           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.324           ms/op
ClientPb.existUser                      sample  176143   5.445 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.438           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.873           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.781           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.797           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.132           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.947           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.556           ms/op
ClientPb.getUser                        sample  168846   5.683 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.358           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.160           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.339           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.255           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.052           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.321           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.224           ms/op
ClientPb.listUser                       sample  147180   6.521 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.871           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.086           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.273           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.976           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.963           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.901           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.047           ms/op
