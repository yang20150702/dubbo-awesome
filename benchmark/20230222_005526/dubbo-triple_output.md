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
# Warmup Iteration   1: 1.568 ops/ms
# Warmup Iteration   2: 3.483 ops/ms
# Warmup Iteration   3: 6.896 ops/ms
Iteration   1: 7.101 ops/ms
Iteration   2: 7.803 ops/ms
Iteration   3: 7.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.602 ±(99.9%) 7.955 ops/ms [Average]
  (min, avg, max) = (7.101, 7.602, 7.901), stdev = 0.436
  CI (99.9%): [≈ 0, 15.557] (assumes normal distribution)


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
# Warmup Iteration   1: 2.321 ops/ms
# Warmup Iteration   2: 6.850 ops/ms
# Warmup Iteration   3: 8.301 ops/ms
Iteration   1: 8.122 ops/ms
Iteration   2: 8.491 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.381 ±(99.9%) 4.103 ops/ms [Average]
  (min, avg, max) = (8.122, 8.381, 8.529), stdev = 0.225
  CI (99.9%): [4.278, 12.484] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.406 ops/ms
# Warmup Iteration   2: 6.725 ops/ms
# Warmup Iteration   3: 7.885 ops/ms
Iteration   1: 8.031 ops/ms
Iteration   2: 7.944 ops/ms
Iteration   3: 7.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.943 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (7.855, 7.943, 8.031), stdev = 0.088
  CI (99.9%): [6.337, 9.549] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.181 ops/ms
# Warmup Iteration   2: 6.077 ops/ms
# Warmup Iteration   3: 6.583 ops/ms
Iteration   1: 6.671 ops/ms
Iteration   2: 6.878 ops/ms
Iteration   3: 7.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.906 ±(99.9%) 4.545 ops/ms [Average]
  (min, avg, max) = (6.671, 6.906, 7.167), stdev = 0.249
  CI (99.9%): [2.361, 11.450] (assumes normal distribution)


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
# Warmup Iteration   1: 11.645 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.011 ms/op
Iteration   1: 4.103 ±(99.9%) 0.008 ms/op
Iteration   2: 4.043 ±(99.9%) 0.003 ms/op
Iteration   3: 3.980 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.042 ±(99.9%) 1.119 ms/op [Average]
  (min, avg, max) = (3.980, 4.042, 4.103), stdev = 0.061
  CI (99.9%): [2.923, 5.161] (assumes normal distribution)


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
# Warmup Iteration   1: 13.516 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.651 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.003 ms/op
Iteration   1: 3.792 ±(99.9%) 0.008 ms/op
Iteration   2: 3.755 ±(99.9%) 0.010 ms/op
Iteration   3: 3.851 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.799 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.755, 3.799, 3.851), stdev = 0.048
  CI (99.9%): [2.920, 4.679] (assumes normal distribution)


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
# Warmup Iteration   1: 12.629 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.773 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.013 ms/op
Iteration   1: 4.005 ±(99.9%) 0.005 ms/op
Iteration   2: 3.888 ±(99.9%) 0.008 ms/op
Iteration   3: 3.909 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.934 ±(99.9%) 1.134 ms/op [Average]
  (min, avg, max) = (3.888, 3.934, 4.005), stdev = 0.062
  CI (99.9%): [2.800, 5.067] (assumes normal distribution)


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
# Warmup Iteration   1: 13.499 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.316 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.012 ±(99.9%) 0.008 ms/op
Iteration   1: 4.812 ±(99.9%) 0.010 ms/op
Iteration   2: 4.735 ±(99.9%) 0.013 ms/op
Iteration   3: 4.543 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.697 ±(99.9%) 2.528 ms/op [Average]
  (min, avg, max) = (4.543, 4.697, 4.812), stdev = 0.139
  CI (99.9%): [2.169, 7.225] (assumes normal distribution)


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
# Warmup Iteration   1: 13.529 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.743 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.383 ±(99.9%) 0.017 ms/op
Iteration   1: 3.975 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.572 ms/op
                 createUser·p0.999:  11.502 ms/op
                 createUser·p0.9999: 23.427 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 4.028 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   6.806 ms/op
                 createUser·p0.999:  22.470 ms/op
                 createUser·p0.9999: 24.744 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  13.993 ms/op
                 createUser·p0.9999: 28.471 ms/op
                 createUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241226
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 527 
    [ 2.500,  5.000) = 225820 
    [ 5.000,  7.500) = 13481 
    [ 7.500, 10.000) = 858 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     15.747 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     28.847 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 11.431 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.011 ms/op
Iteration   1: 3.956 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.931 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   7.684 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 23.918 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.903 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.876 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   7.691 ms/op
                 existUser·p0.999:  15.405 ms/op
                 existUser·p0.9999: 29.458 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   3: 3.808 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  27.591 ms/op
                 existUser·p0.9999: 32.283 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246702
  mean =      3.888 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196 
    [ 2.500,  5.000) = 235544 
    [ 5.000,  7.500) = 8569 
    [ 7.500, 10.000) = 1713 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.657 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.454 ms/op
     p(99.9000) =     15.357 ms/op
     p(99.9900) =     30.692 ms/op
     p(99.9990) =     35.066 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 11.160 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.015 ms/op
Iteration   1: 4.187 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  17.157 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 3.933 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  14.579 ms/op
                 getUser·p0.9999: 28.251 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   3: 4.102 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.466 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   7.684 ms/op
                 getUser·p0.999:  28.805 ms/op
                 getUser·p0.9999: 30.736 ms/op
                 getUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235764
  mean =      4.071 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 219998 
    [ 5.000,  7.500) = 13334 
    [ 7.500, 10.000) = 1607 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     32.134 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 14.253 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.231 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.916 ±(99.9%) 0.016 ms/op
Iteration   1: 4.894 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  24.478 ms/op
                 listUser·p0.9999: 29.324 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   2: 4.766 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.188 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  20.273 ms/op
                 listUser·p0.9999: 26.487 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 4.725 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  17.182 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200162
  mean =      4.794 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 165395 
    [ 5.000,  7.500) = 29314 
    [ 7.500, 10.000) = 4391 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     30.342 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.602 ± 7.955  ops/ms
ClientPb.existUser                       thrpt       3   8.381 ± 4.103  ops/ms
ClientPb.getUser                         thrpt       3   7.943 ± 1.606  ops/ms
ClientPb.listUser                        thrpt       3   6.906 ± 4.545  ops/ms
ClientPb.createUser                       avgt       3   4.042 ± 1.119   ms/op
ClientPb.existUser                        avgt       3   3.799 ± 0.879   ms/op
ClientPb.getUser                          avgt       3   3.934 ± 1.134   ms/op
ClientPb.listUser                         avgt       3   4.697 ± 2.528   ms/op
ClientPb.createUser                     sample  241226   3.976 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.343           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.747           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.722           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.934           ms/op
ClientPb.existUser                      sample  246702   3.888 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.657           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.454           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.357           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.692           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  235764   4.071 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.057           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.219           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.048           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.145           ms/op
ClientPb.listUser                       sample  200162   4.794 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.169           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.968           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.900           ms/op
