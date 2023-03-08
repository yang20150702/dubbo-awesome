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
# Warmup Iteration   1: 1.034 ops/ms
# Warmup Iteration   2: 2.428 ops/ms
# Warmup Iteration   3: 4.931 ops/ms
Iteration   1: 5.619 ops/ms
Iteration   2: 6.236 ops/ms
Iteration   3: 5.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.943 ±(99.9%) 5.642 ops/ms [Average]
  (min, avg, max) = (5.619, 5.943, 6.236), stdev = 0.309
  CI (99.9%): [0.300, 11.585] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.577 ops/ms
# Warmup Iteration   2: 5.090 ops/ms
# Warmup Iteration   3: 6.265 ops/ms
Iteration   1: 6.315 ops/ms
Iteration   2: 6.576 ops/ms
Iteration   3: 6.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.496 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (6.315, 6.496, 6.598), stdev = 0.158
  CI (99.9%): [3.619, 9.374] (assumes normal distribution)


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
# Warmup Iteration   1: 1.833 ops/ms
# Warmup Iteration   2: 4.869 ops/ms
# Warmup Iteration   3: 5.683 ops/ms
Iteration   1: 5.491 ops/ms
Iteration   2: 5.321 ops/ms
Iteration   3: 5.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.502 ±(99.9%) 3.415 ops/ms [Average]
  (min, avg, max) = (5.321, 5.502, 5.694), stdev = 0.187
  CI (99.9%): [2.087, 8.917] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.502 ops/ms
# Warmup Iteration   2: 3.551 ops/ms
# Warmup Iteration   3: 4.626 ops/ms
Iteration   1: 4.765 ops/ms
Iteration   2: 4.843 ops/ms
Iteration   3: 4.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.854 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (4.765, 4.854, 4.954), stdev = 0.095
  CI (99.9%): [3.124, 6.583] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 22.849 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 7.472 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.010 ±(99.9%) 0.013 ms/op
Iteration   1: 6.074 ±(99.9%) 0.013 ms/op
Iteration   2: 5.527 ±(99.9%) 0.023 ms/op
Iteration   3: 5.793 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.798 ±(99.9%) 4.984 ms/op [Average]
  (min, avg, max) = (5.527, 5.798, 6.074), stdev = 0.273
  CI (99.9%): [0.814, 10.782] (assumes normal distribution)


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
# Warmup Iteration   1: 18.509 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.191 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.580 ±(99.9%) 0.012 ms/op
Iteration   1: 5.575 ±(99.9%) 0.013 ms/op
Iteration   2: 5.624 ±(99.9%) 0.013 ms/op
Iteration   3: 5.595 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.598 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (5.575, 5.598, 5.624), stdev = 0.025
  CI (99.9%): [5.148, 6.048] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.609 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 7.201 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.895 ±(99.9%) 0.012 ms/op
Iteration   1: 5.918 ±(99.9%) 0.015 ms/op
Iteration   2: 5.984 ±(99.9%) 0.010 ms/op
Iteration   3: 5.843 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.915 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (5.843, 5.915, 5.984), stdev = 0.071
  CI (99.9%): [4.623, 7.207] (assumes normal distribution)


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
# Warmup Iteration   1: 20.327 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 8.100 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 7.025 ±(99.9%) 0.016 ms/op
Iteration   1: 6.873 ±(99.9%) 0.015 ms/op
Iteration   2: 6.465 ±(99.9%) 0.019 ms/op
Iteration   3: 6.188 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.509 ±(99.9%) 6.293 ms/op [Average]
  (min, avg, max) = (6.188, 6.509, 6.873), stdev = 0.345
  CI (99.9%): [0.215, 12.802] (assumes normal distribution)


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
# Warmup Iteration   1: 18.074 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.982 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.768 ±(99.9%) 0.024 ms/op
Iteration   1: 5.257 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.398 ms/op
                 createUser·p0.95:   7.504 ms/op
                 createUser·p0.99:   10.617 ms/op
                 createUser·p0.999:  23.603 ms/op
                 createUser·p0.9999: 26.342 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 5.058 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.441 ms/op
                 createUser·p0.50:   4.801 ms/op
                 createUser·p0.90:   5.882 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  25.943 ms/op
                 createUser·p0.9999: 29.930 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   3: 5.250 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   7.234 ms/op
                 createUser·p0.99:   10.163 ms/op
                 createUser·p0.999:  27.592 ms/op
                 createUser·p0.9999: 30.596 ms/op
                 createUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185091
  mean =      5.186 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 106255 
    [ 5.000,  7.500) = 71060 
    [ 7.500, 10.000) = 5797 
    [10.000, 12.500) = 1170 
    [12.500, 15.000) = 371 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     25.517 ms/op
     p(99.9900) =     29.441 ms/op
     p(99.9990) =     32.807 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 16.496 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.976 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.093 ±(99.9%) 0.017 ms/op
Iteration   1: 5.183 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.429 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   8.020 ms/op
                 existUser·p0.99:   11.862 ms/op
                 existUser·p0.999:  23.599 ms/op
                 existUser·p0.9999: 28.404 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   2: 5.225 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.135 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  15.021 ms/op
                 existUser·p0.9999: 24.794 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 5.195 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.499 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.340 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  25.477 ms/op
                 existUser·p0.9999: 29.055 ms/op
                 existUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184391
  mean =      5.201 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 103673 
    [ 5.000,  7.500) = 71639 
    [ 7.500, 10.000) = 6892 
    [10.000, 12.500) = 1363 
    [12.500, 15.000) = 504 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     21.044 ms/op
     p(99.9900) =     28.465 ms/op
     p(99.9990) =     29.708 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 17.310 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.461 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.416 ±(99.9%) 0.016 ms/op
Iteration   1: 5.458 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.660 ms/op
                 getUser·p0.95:   8.339 ms/op
                 getUser·p0.99:   12.616 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 25.690 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 5.379 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.441 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.308 ms/op
                 getUser·p0.95:   7.332 ms/op
                 getUser·p0.99:   10.764 ms/op
                 getUser·p0.999:  22.725 ms/op
                 getUser·p0.9999: 29.822 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   3: 5.459 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   6.636 ms/op
                 getUser·p0.95:   7.758 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  23.436 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176637
  mean =      5.432 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 70762 
    [ 5.000,  7.500) = 95888 
    [ 7.500, 10.000) = 6964 
    [10.000, 12.500) = 1929 
    [12.500, 15.000) = 724 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     22.786 ms/op
     p(99.9900) =     28.486 ms/op
     p(99.9990) =     30.542 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 17.091 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.954 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.546 ±(99.9%) 0.028 ms/op
Iteration   1: 6.425 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   9.404 ms/op
                 listUser·p0.99:   13.074 ms/op
                 listUser·p0.999:  29.932 ms/op
                 listUser·p0.9999: 32.212 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 6.132 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.547 ms/op
                 listUser·p0.999:  27.787 ms/op
                 listUser·p0.9999: 30.795 ms/op
                 listUser·p1.00:   32.408 ms/op

Iteration   3: 6.059 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.006 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.883 ms/op
                 listUser·p0.999:  25.476 ms/op
                 listUser·p0.9999: 29.539 ms/op
                 listUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154768
  mean =      6.201 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 8353 
    [ 5.000,  7.500) = 130838 
    [ 7.500, 10.000) = 11395 
    [10.000, 12.500) = 2792 
    [12.500, 15.000) = 761 
    [15.000, 17.500) = 263 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 115 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.150 ms/op
     p(50.0000) =      5.800 ms/op
     p(90.0000) =      7.512 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     27.959 ms/op
     p(99.9900) =     31.459 ms/op
     p(99.9990) =     34.174 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.943 ± 5.642  ops/ms
ClientPb.existUser                       thrpt       3   6.496 ± 2.877  ops/ms
ClientPb.getUser                         thrpt       3   5.502 ± 3.415  ops/ms
ClientPb.listUser                        thrpt       3   4.854 ± 1.730  ops/ms
ClientPb.createUser                       avgt       3   5.798 ± 4.984   ms/op
ClientPb.existUser                        avgt       3   5.598 ± 0.450   ms/op
ClientPb.getUser                          avgt       3   5.915 ± 1.292   ms/op
ClientPb.listUser                         avgt       3   6.509 ± 6.293   ms/op
ClientPb.createUser                     sample  185091   5.186 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.891           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.176           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.240           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.517           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.441           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.030           ms/op
ClientPb.existUser                      sample  184391   5.201 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.179           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.341           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.471           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.371           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.044           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.465           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.819           ms/op
ClientPb.getUser                        sample  176637   5.432 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.784           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.799           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.272           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.786           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.486           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  154768   6.201 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.150           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.124           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.459           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.210           ms/op
