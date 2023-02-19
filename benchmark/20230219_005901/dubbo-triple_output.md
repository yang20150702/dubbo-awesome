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
# Warmup Iteration   1: 1.611 ops/ms
# Warmup Iteration   2: 3.583 ops/ms
# Warmup Iteration   3: 7.163 ops/ms
Iteration   1: 7.578 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.893 ±(99.9%) 5.864 ops/ms [Average]
  (min, avg, max) = (7.578, 7.893, 8.221), stdev = 0.321
  CI (99.9%): [2.029, 13.757] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.359 ops/ms
# Warmup Iteration   2: 6.555 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.119 ops/ms
Iteration   2: 8.402 ops/ms
Iteration   3: 8.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.265 ±(99.9%) 2.589 ops/ms [Average]
  (min, avg, max) = (8.119, 8.265, 8.402), stdev = 0.142
  CI (99.9%): [5.676, 10.854] (assumes normal distribution)


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
# Warmup Iteration   1: 2.473 ops/ms
# Warmup Iteration   2: 6.304 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 7.840 ops/ms
Iteration   2: 8.013 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.019 ±(99.9%) 3.311 ops/ms [Average]
  (min, avg, max) = (7.840, 8.019, 8.203), stdev = 0.181
  CI (99.9%): [4.708, 11.330] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 5.440 ops/ms
# Warmup Iteration   3: 6.752 ops/ms
Iteration   1: 6.444 ops/ms
Iteration   2: 6.733 ops/ms
Iteration   3: 6.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.698 ±(99.9%) 4.355 ops/ms [Average]
  (min, avg, max) = (6.444, 6.698, 6.917), stdev = 0.239
  CI (99.9%): [2.343, 11.053] (assumes normal distribution)


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
# Warmup Iteration   1: 12.945 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.010 ms/op
Iteration   1: 4.029 ±(99.9%) 0.005 ms/op
Iteration   2: 4.013 ±(99.9%) 0.004 ms/op
Iteration   3: 4.234 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.092 ±(99.9%) 2.246 ms/op [Average]
  (min, avg, max) = (4.013, 4.092, 4.234), stdev = 0.123
  CI (99.9%): [1.846, 6.338] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.546 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.007 ms/op
Iteration   1: 3.942 ±(99.9%) 0.010 ms/op
Iteration   2: 3.884 ±(99.9%) 0.007 ms/op
Iteration   3: 3.883 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.903 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (3.883, 3.903, 3.942), stdev = 0.034
  CI (99.9%): [3.282, 4.524] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.031 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.573 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.011 ms/op
Iteration   1: 3.834 ±(99.9%) 0.010 ms/op
Iteration   2: 3.878 ±(99.9%) 0.010 ms/op
Iteration   3: 4.042 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.918 ±(99.9%) 1.998 ms/op [Average]
  (min, avg, max) = (3.834, 3.918, 4.042), stdev = 0.110
  CI (99.9%): [1.920, 5.917] (assumes normal distribution)


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
# Warmup Iteration   1: 13.249 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.580 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.882 ±(99.9%) 0.008 ms/op
Iteration   1: 4.602 ±(99.9%) 0.011 ms/op
Iteration   2: 4.595 ±(99.9%) 0.011 ms/op
Iteration   3: 4.694 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.631 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (4.595, 4.631, 4.694), stdev = 0.055
  CI (99.9%): [3.620, 5.641] (assumes normal distribution)


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
# Warmup Iteration   1: 12.087 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.858 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.328 ±(99.9%) 0.017 ms/op
Iteration   1: 3.854 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  11.991 ms/op
                 createUser·p0.9999: 24.983 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   2: 4.053 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  24.558 ms/op
                 createUser·p0.9999: 27.984 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 3.966 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  24.730 ms/op
                 createUser·p0.9999: 32.156 ms/op
                 createUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242578
  mean =      3.956 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 537 
    [ 2.500,  5.000) = 231092 
    [ 5.000,  7.500) = 8910 
    [ 7.500, 10.000) = 1519 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     22.913 ms/op
     p(99.9900) =     29.588 ms/op
     p(99.9990) =     37.065 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 11.587 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.012 ms/op
Iteration   1: 3.795 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  22.536 ms/op
                 existUser·p0.9999: 25.021 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.883 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.886 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  13.763 ms/op
                 existUser·p0.9999: 27.354 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 3.920 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.749 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  17.118 ms/op
                 existUser·p0.9999: 30.371 ms/op
                 existUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248199
  mean =      3.865 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 259 
    [ 2.500,  5.000) = 236231 
    [ 5.000,  7.500) = 10253 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     17.321 ms/op
     p(99.9900) =     29.169 ms/op
     p(99.9990) =     31.312 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 13.539 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.787 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.012 ms/op
Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.019 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  22.499 ms/op
                 getUser·p0.9999: 25.395 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   2: 3.833 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  24.968 ms/op
                 getUser·p0.9999: 27.350 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   3: 3.983 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.302 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  14.276 ms/op
                 getUser·p0.9999: 28.212 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244229
  mean =      3.930 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 235529 
    [ 5.000,  7.500) = 7187 
    [ 7.500, 10.000) = 784 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 116 

  Percentiles, ms/op:
      p(0.0000) =      1.806 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     28.479 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 14.729 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 5.874 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.893 ±(99.9%) 0.019 ms/op
Iteration   1: 4.783 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  25.372 ms/op
                 listUser·p0.9999: 28.606 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   2: 4.757 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 25.487 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 4.926 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.955 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  17.831 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199040
  mean =      4.821 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 159332 
    [ 5.000,  7.500) = 33838 
    [ 7.500, 10.000) = 4759 
    [10.000, 12.500) = 523 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     20.872 ms/op
     p(99.9900) =     27.109 ms/op
     p(99.9990) =     29.002 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.893 ± 5.864  ops/ms
ClientPb.existUser                       thrpt       3   8.265 ± 2.589  ops/ms
ClientPb.getUser                         thrpt       3   8.019 ± 3.311  ops/ms
ClientPb.listUser                        thrpt       3   6.698 ± 4.355  ops/ms
ClientPb.createUser                       avgt       3   4.092 ± 2.246   ms/op
ClientPb.existUser                        avgt       3   3.903 ± 0.621   ms/op
ClientPb.getUser                          avgt       3   3.918 ± 1.998   ms/op
ClientPb.listUser                         avgt       3   4.631 ± 1.011   ms/op
ClientPb.createUser                     sample  242578   3.956 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.196           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.045           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.913           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.588           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.224           ms/op
ClientPb.existUser                      sample  248199   3.865 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.090           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.169           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.588           ms/op
ClientPb.getUser                        sample  244229   3.930 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.806           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.217           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.886           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.541           ms/op
ClientPb.listUser                       sample  199040   4.821 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.134           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.078           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.872           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.109           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.229           ms/op
