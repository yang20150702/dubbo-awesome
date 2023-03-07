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
# Warmup Iteration   1: 1.603 ops/ms
# Warmup Iteration   2: 3.972 ops/ms
# Warmup Iteration   3: 7.337 ops/ms
Iteration   1: 7.619 ops/ms
Iteration   2: 8.006 ops/ms
Iteration   3: 7.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.815 ±(99.9%) 3.529 ops/ms [Average]
  (min, avg, max) = (7.619, 7.815, 8.006), stdev = 0.193
  CI (99.9%): [4.286, 11.343] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.072 ops/ms
# Warmup Iteration   2: 6.891 ops/ms
# Warmup Iteration   3: 8.080 ops/ms
Iteration   1: 8.095 ops/ms
Iteration   2: 8.284 ops/ms
Iteration   3: 8.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.288 ±(99.9%) 3.559 ops/ms [Average]
  (min, avg, max) = (8.095, 8.288, 8.485), stdev = 0.195
  CI (99.9%): [4.728, 11.847] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.276 ops/ms
# Warmup Iteration   2: 6.440 ops/ms
# Warmup Iteration   3: 7.624 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 8.460 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.162 ±(99.9%) 5.849 ops/ms [Average]
  (min, avg, max) = (7.823, 8.162, 8.460), stdev = 0.321
  CI (99.9%): [2.313, 14.012] (assumes normal distribution)


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
# Warmup Iteration   1: 2.225 ops/ms
# Warmup Iteration   2: 5.770 ops/ms
# Warmup Iteration   3: 6.859 ops/ms
Iteration   1: 7.103 ops/ms
Iteration   2: 7.088 ops/ms
Iteration   3: 6.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.051 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (6.962, 7.051, 7.103), stdev = 0.078
  CI (99.9%): [5.633, 8.469] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.488 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.814 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.003 ms/op
Iteration   1: 3.911 ±(99.9%) 0.007 ms/op
Iteration   2: 4.099 ±(99.9%) 0.004 ms/op
Iteration   3: 4.132 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.047 ±(99.9%) 2.169 ms/op [Average]
  (min, avg, max) = (3.911, 4.047, 4.132), stdev = 0.119
  CI (99.9%): [1.878, 6.216] (assumes normal distribution)


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
# Warmup Iteration   1: 11.613 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.004 ms/op
Iteration   1: 3.746 ±(99.9%) 0.009 ms/op
Iteration   2: 3.789 ±(99.9%) 0.004 ms/op
Iteration   3: 3.812 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.782 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.746, 3.782, 3.812), stdev = 0.034
  CI (99.9%): [3.168, 4.396] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.224 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.004 ms/op
Iteration   1: 4.158 ±(99.9%) 0.005 ms/op
Iteration   2: 3.851 ±(99.9%) 0.010 ms/op
Iteration   3: 4.382 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.130 ±(99.9%) 4.866 ms/op [Average]
  (min, avg, max) = (3.851, 4.130, 4.382), stdev = 0.267
  CI (99.9%): [≈ 0, 8.997] (assumes normal distribution)


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
# Warmup Iteration   1: 15.240 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.538 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.621 ±(99.9%) 0.015 ms/op
Iteration   1: 4.682 ±(99.9%) 0.005 ms/op
Iteration   2: 4.597 ±(99.9%) 0.011 ms/op
Iteration   3: 4.560 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.613 ±(99.9%) 1.140 ms/op [Average]
  (min, avg, max) = (4.560, 4.613, 4.682), stdev = 0.062
  CI (99.9%): [3.473, 5.753] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.426 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 5.190 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.440 ±(99.9%) 0.019 ms/op
Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.952 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  12.681 ms/op
                 createUser·p0.9999: 29.759 ms/op
                 createUser·p1.00:   30.900 ms/op

Iteration   2: 4.083 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  25.362 ms/op
                 createUser·p0.9999: 28.082 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 4.213 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   8.045 ms/op
                 createUser·p0.999:  22.293 ms/op
                 createUser·p0.9999: 30.403 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234048
  mean =      4.099 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 215268 
    [ 5.000,  7.500) = 15638 
    [ 7.500, 10.000) = 2014 
    [10.000, 12.500) = 497 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      7.901 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     29.937 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 11.145 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.014 ms/op
Iteration   1: 3.790 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  22.151 ms/op
                 existUser·p0.9999: 24.150 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.901 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   7.119 ms/op
                 existUser·p0.999:  16.564 ms/op
                 existUser·p0.9999: 25.231 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 3.841 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.831 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  15.598 ms/op
                 existUser·p0.9999: 27.361 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249673
  mean =      3.844 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 315 
    [ 2.500,  5.000) = 240368 
    [ 5.000,  7.500) = 7450 
    [ 7.500, 10.000) = 826 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     26.674 ms/op
     p(99.9990) =     27.705 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 13.544 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.936 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.017 ms/op
Iteration   1: 4.106 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 27.197 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 4.040 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  25.592 ms/op
                 getUser·p0.9999: 28.249 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  12.689 ms/op
                 getUser·p0.9999: 31.356 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237693
  mean =      4.039 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 223156 
    [ 5.000,  7.500) = 10721 
    [ 7.500, 10.000) = 2770 
    [10.000, 12.500) = 606 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     30.441 ms/op
     p(99.9990) =     32.895 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 14.344 ±(99.9%) 0.216 ms/op
# Warmup Iteration   2: 5.893 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.811 ±(99.9%) 0.018 ms/op
Iteration   1: 4.549 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  25.035 ms/op
                 listUser·p0.9999: 27.263 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   2: 4.664 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   8.903 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 22.526 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.638 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 25.671 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 207785
  mean =      4.616 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 184672 
    [ 5.000,  7.500) = 19089 
    [ 7.500, 10.000) = 2765 
    [10.000, 12.500) = 539 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 91 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     20.880 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.517 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.815 ± 3.529  ops/ms
ClientPb.existUser                       thrpt       3   8.288 ± 3.559  ops/ms
ClientPb.getUser                         thrpt       3   8.162 ± 5.849  ops/ms
ClientPb.listUser                        thrpt       3   7.051 ± 1.418  ops/ms
ClientPb.createUser                       avgt       3   4.047 ± 2.169   ms/op
ClientPb.existUser                        avgt       3   3.782 ± 0.614   ms/op
ClientPb.getUser                          avgt       3   4.130 ± 4.866   ms/op
ClientPb.listUser                         avgt       3   4.613 ± 1.140   ms/op
ClientPb.createUser                     sample  234048   4.099 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.879           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.841           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.901           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.184           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.937           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999           ms/op
ClientPb.existUser                      sample  249673   3.844 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.343           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.597           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.674           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.787           ms/op
ClientPb.getUser                        sample  237693   4.039 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.405           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.087           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.441           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  207785   4.616 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.739           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.054           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.880           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.542           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.148           ms/op
