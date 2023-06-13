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
# Warmup Iteration   1: 1.688 ops/ms
# Warmup Iteration   2: 3.743 ops/ms
# Warmup Iteration   3: 7.333 ops/ms
Iteration   1: 7.557 ops/ms
Iteration   2: 7.810 ops/ms
Iteration   3: 7.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.715 ±(99.9%) 2.516 ops/ms [Average]
  (min, avg, max) = (7.557, 7.715, 7.810), stdev = 0.138
  CI (99.9%): [5.199, 10.231] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.314 ops/ms
# Warmup Iteration   2: 7.114 ops/ms
# Warmup Iteration   3: 8.289 ops/ms
Iteration   1: 8.730 ops/ms
Iteration   2: 8.309 ops/ms
Iteration   3: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.502 ±(99.9%) 3.882 ops/ms [Average]
  (min, avg, max) = (8.309, 8.502, 8.730), stdev = 0.213
  CI (99.9%): [4.620, 12.384] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.519 ops/ms
# Warmup Iteration   2: 7.254 ops/ms
# Warmup Iteration   3: 8.013 ops/ms
Iteration   1: 8.161 ops/ms
Iteration   2: 8.314 ops/ms
Iteration   3: 8.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.314 ±(99.9%) 2.809 ops/ms [Average]
  (min, avg, max) = (8.161, 8.314, 8.469), stdev = 0.154
  CI (99.9%): [5.505, 11.123] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.357 ops/ms
# Warmup Iteration   2: 5.952 ops/ms
# Warmup Iteration   3: 6.804 ops/ms
Iteration   1: 6.813 ops/ms
Iteration   2: 7.203 ops/ms
Iteration   3: 6.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.004 ±(99.9%) 3.561 ops/ms [Average]
  (min, avg, max) = (6.813, 7.004, 7.203), stdev = 0.195
  CI (99.9%): [3.443, 10.565] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.229 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.085 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.313 ±(99.9%) 0.006 ms/op
Iteration   1: 3.995 ±(99.9%) 0.006 ms/op
Iteration   2: 3.798 ±(99.9%) 0.008 ms/op
Iteration   3: 3.794 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.862 ±(99.9%) 2.094 ms/op [Average]
  (min, avg, max) = (3.794, 3.862, 3.995), stdev = 0.115
  CI (99.9%): [1.768, 5.956] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 11.772 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.004 ms/op
Iteration   1: 3.909 ±(99.9%) 0.006 ms/op
Iteration   2: 3.903 ±(99.9%) 0.006 ms/op
Iteration   3: 3.894 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.902 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (3.894, 3.902, 3.909), stdev = 0.008
  CI (99.9%): [3.765, 4.039] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.645 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.009 ms/op
Iteration   1: 3.757 ±(99.9%) 0.005 ms/op
Iteration   2: 3.777 ±(99.9%) 0.011 ms/op
Iteration   3: 3.752 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.762 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.752, 3.762, 3.777), stdev = 0.013
  CI (99.9%): [3.527, 3.997] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.732 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.651 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.596 ±(99.9%) 0.007 ms/op
Iteration   1: 4.543 ±(99.9%) 0.007 ms/op
Iteration   2: 4.509 ±(99.9%) 0.013 ms/op
Iteration   3: 4.372 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.475 ±(99.9%) 1.646 ms/op [Average]
  (min, avg, max) = (4.372, 4.475, 4.543), stdev = 0.090
  CI (99.9%): [2.829, 6.120] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.291 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.625 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.015 ms/op
Iteration   1: 3.888 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  14.495 ms/op
                 createUser·p0.9999: 25.388 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   2: 4.046 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.978 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  13.631 ms/op
                 createUser·p0.9999: 33.698 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   3: 3.872 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  27.066 ms/op
                 createUser·p0.9999: 31.857 ms/op
                 createUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243888
  mean =      3.934 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 329 
    [ 2.500,  5.000) = 230476 
    [ 5.000,  7.500) = 11091 
    [ 7.500, 10.000) = 1354 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     23.174 ms/op
     p(99.9900) =     31.903 ms/op
     p(99.9990) =     34.021 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.425 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.010 ms/op
Iteration   1: 4.028 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   8.159 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 24.874 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   2: 3.888 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  23.953 ms/op
                 existUser·p0.9999: 25.952 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.883 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.361 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 26.903 ms/op
                 existUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244234
  mean =      3.932 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 528 
    [ 2.500,  5.000) = 228387 
    [ 5.000,  7.500) = 13099 
    [ 7.500, 10.000) = 1574 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     14.771 ms/op
     p(99.9900) =     26.692 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.389 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.015 ms/op
Iteration   1: 3.850 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  13.253 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  12.641 ms/op
                 getUser·p0.9999: 29.317 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   3: 4.100 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  29.427 ms/op
                 getUser·p0.9999: 35.272 ms/op
                 getUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239458
  mean =      4.006 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 226 
    [ 2.500,  5.000) = 223745 
    [ 5.000,  7.500) = 12773 
    [ 7.500, 10.000) = 1859 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     33.886 ms/op
     p(99.9990) =     37.968 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.529 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.440 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.019 ms/op
Iteration   1: 4.911 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   7.207 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  27.819 ms/op
                 listUser·p0.9999: 34.603 ms/op
                 listUser·p1.00:   35.455 ms/op

Iteration   2: 4.650 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  16.421 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 4.472 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  16.374 ms/op
                 listUser·p0.9999: 18.329 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205404
  mean =      4.671 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 175623 
    [ 5.000,  7.500) = 24561 
    [ 7.500, 10.000) = 3973 
    [10.000, 12.500) = 629 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     19.791 ms/op
     p(99.9900) =     34.174 ms/op
     p(99.9990) =     34.986 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.715 ± 2.516  ops/ms
ClientPb.existUser                       thrpt       3   8.502 ± 3.882  ops/ms
ClientPb.getUser                         thrpt       3   8.314 ± 2.809  ops/ms
ClientPb.listUser                        thrpt       3   7.004 ± 3.561  ops/ms
ClientPb.createUser                       avgt       3   3.862 ± 2.094   ms/op
ClientPb.existUser                        avgt       3   3.902 ± 0.137   ms/op
ClientPb.getUser                          avgt       3   3.762 ± 0.235   ms/op
ClientPb.listUser                         avgt       3   4.475 ± 1.646   ms/op
ClientPb.createUser                     sample  243888   3.934 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.686           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.174           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.903           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  244234   3.932 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.361           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.596           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.771           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.692           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.213           ms/op
ClientPb.getUser                        sample  239458   4.006 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.499           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.733           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.886           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.666           ms/op
ClientPb.listUser                       sample  205404   4.671 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.177           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.906           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.791           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.455           ms/op
