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
# Warmup Iteration   1: 1.809 ops/ms
# Warmup Iteration   2: 3.494 ops/ms
# Warmup Iteration   3: 7.284 ops/ms
Iteration   1: 7.578 ops/ms
Iteration   2: 8.369 ops/ms
Iteration   3: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.108 ±(99.9%) 8.361 ops/ms [Average]
  (min, avg, max) = (7.578, 8.108, 8.376), stdev = 0.458
  CI (99.9%): [≈ 0, 16.469] (assumes normal distribution)


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
# Warmup Iteration   1: 2.414 ops/ms
# Warmup Iteration   2: 7.251 ops/ms
# Warmup Iteration   3: 8.374 ops/ms
Iteration   1: 8.926 ops/ms
Iteration   2: 8.986 ops/ms
Iteration   3: 8.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.950 ±(99.9%) 0.573 ops/ms [Average]
  (min, avg, max) = (8.926, 8.950, 8.986), stdev = 0.031
  CI (99.9%): [8.378, 9.523] (assumes normal distribution)


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
# Warmup Iteration   1: 2.285 ops/ms
# Warmup Iteration   2: 6.598 ops/ms
# Warmup Iteration   3: 7.864 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.235 ±(99.9%) 4.635 ops/ms [Average]
  (min, avg, max) = (8.006, 8.235, 8.508), stdev = 0.254
  CI (99.9%): [3.600, 12.870] (assumes normal distribution)


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
# Warmup Iteration   1: 2.118 ops/ms
# Warmup Iteration   2: 5.607 ops/ms
# Warmup Iteration   3: 6.569 ops/ms
Iteration   1: 6.856 ops/ms
Iteration   2: 6.865 ops/ms
Iteration   3: 7.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.933 ±(99.9%) 2.289 ops/ms [Average]
  (min, avg, max) = (6.856, 6.933, 7.078), stdev = 0.125
  CI (99.9%): [4.644, 9.221] (assumes normal distribution)


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
# Warmup Iteration   1: 12.100 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.009 ms/op
Iteration   1: 3.848 ±(99.9%) 0.012 ms/op
Iteration   2: 3.771 ±(99.9%) 0.010 ms/op
Iteration   3: 3.839 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.819 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.771, 3.819, 3.848), stdev = 0.042
  CI (99.9%): [3.056, 4.583] (assumes normal distribution)


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
# Warmup Iteration   1: 10.794 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.011 ms/op
Iteration   1: 3.941 ±(99.9%) 0.004 ms/op
Iteration   2: 3.603 ±(99.9%) 0.007 ms/op
Iteration   3: 3.637 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.727 ±(99.9%) 3.396 ms/op [Average]
  (min, avg, max) = (3.603, 3.727, 3.941), stdev = 0.186
  CI (99.9%): [0.331, 7.122] (assumes normal distribution)


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
# Warmup Iteration   1: 12.486 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.012 ms/op
Iteration   1: 4.024 ±(99.9%) 0.009 ms/op
Iteration   2: 3.867 ±(99.9%) 0.008 ms/op
Iteration   3: 3.867 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.919 ±(99.9%) 1.653 ms/op [Average]
  (min, avg, max) = (3.867, 3.919, 4.024), stdev = 0.091
  CI (99.9%): [2.266, 5.572] (assumes normal distribution)


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
# Warmup Iteration   1: 15.681 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.613 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.526 ±(99.9%) 0.014 ms/op
Iteration   1: 4.457 ±(99.9%) 0.014 ms/op
Iteration   2: 4.431 ±(99.9%) 0.013 ms/op
Iteration   3: 4.628 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.506 ±(99.9%) 1.946 ms/op [Average]
  (min, avg, max) = (4.431, 4.506, 4.628), stdev = 0.107
  CI (99.9%): [2.559, 6.452] (assumes normal distribution)


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
# Warmup Iteration   1: 10.697 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.017 ms/op
Iteration   1: 3.852 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.839 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   7.186 ms/op
                 createUser·p0.999:  22.872 ms/op
                 createUser·p0.9999: 26.161 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 3.744 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.978 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  25.825 ms/op
                 createUser·p0.9999: 27.850 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   3: 3.914 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.835 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  15.327 ms/op
                 createUser·p0.9999: 35.455 ms/op
                 createUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 250279
  mean =      3.835 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 676 
    [ 2.500,  5.000) = 240358 
    [ 5.000,  7.500) = 7371 
    [ 7.500, 10.000) = 1328 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 125 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.835 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     21.838 ms/op
     p(99.9900) =     33.873 ms/op
     p(99.9990) =     35.946 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 10.745 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
Iteration   1: 3.887 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  10.384 ms/op
                 existUser·p0.9999: 25.639 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 3.880 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  15.073 ms/op
                 existUser·p0.9999: 36.962 ms/op
                 existUser·p1.00:   39.846 ms/op

Iteration   3: 3.714 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  25.657 ms/op
                 existUser·p0.9999: 32.834 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250735
  mean =      3.825 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1003 
    [ 2.500,  5.000) = 238602 
    [ 5.000,  7.500) = 9515 
    [ 7.500, 10.000) = 1104 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.030 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     37.749 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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
# Warmup Iteration   1: 10.764 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.013 ms/op
Iteration   1: 3.924 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.634 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   8.069 ms/op
                 getUser·p0.999:  12.255 ms/op
                 getUser·p0.9999: 25.226 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   2: 3.815 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.786 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  23.929 ms/op
                 getUser·p0.9999: 26.517 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   3: 3.914 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  15.041 ms/op
                 getUser·p0.9999: 31.795 ms/op
                 getUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247057
  mean =      3.884 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1191 
    [ 2.500,  5.000) = 233604 
    [ 5.000,  7.500) = 10070 
    [ 7.500, 10.000) = 1531 
    [10.000, 12.500) = 398 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     14.958 ms/op
     p(99.9900) =     30.812 ms/op
     p(99.9990) =     32.997 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 13.438 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 5.412 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.822 ±(99.9%) 0.017 ms/op
Iteration   1: 4.550 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.934 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  23.892 ms/op
                 listUser·p0.9999: 27.524 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 4.550 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.568 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  17.640 ms/op
                 listUser·p0.9999: 21.855 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   3: 4.448 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  16.599 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212507
  mean =      4.515 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 192608 
    [ 5.000,  7.500) = 15937 
    [ 7.500, 10.000) = 2948 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     19.939 ms/op
     p(99.9900) =     25.518 ms/op
     p(99.9990) =     27.800 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.108 ± 8.361  ops/ms
ClientPb.existUser                       thrpt       3   8.950 ± 0.573  ops/ms
ClientPb.getUser                         thrpt       3   8.235 ± 4.635  ops/ms
ClientPb.listUser                        thrpt       3   6.933 ± 2.289  ops/ms
ClientPb.createUser                       avgt       3   3.819 ± 0.764   ms/op
ClientPb.existUser                        avgt       3   3.727 ± 3.396   ms/op
ClientPb.getUser                          avgt       3   3.919 ± 1.653   ms/op
ClientPb.listUser                         avgt       3   4.506 ± 1.946   ms/op
ClientPb.createUser                     sample  250279   3.835 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.835           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.768           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.838           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.873           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.045           ms/op
ClientPb.existUser                      sample  250735   3.825 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.799           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.030           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.783           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.846           ms/op
ClientPb.getUser                        sample  247057   3.884 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.280           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.356           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.958           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.812           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.391           ms/op
ClientPb.listUser                       sample  212507   4.515 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.939           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.918           ms/op
