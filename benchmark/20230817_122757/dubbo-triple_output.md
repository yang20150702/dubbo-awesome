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
# Warmup Iteration   1: 1.575 ops/ms
# Warmup Iteration   2: 3.411 ops/ms
# Warmup Iteration   3: 7.039 ops/ms
Iteration   1: 7.374 ops/ms
Iteration   2: 8.064 ops/ms
Iteration   3: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.769 ±(99.9%) 6.488 ops/ms [Average]
  (min, avg, max) = (7.374, 7.769, 8.064), stdev = 0.356
  CI (99.9%): [1.281, 14.257] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.229 ops/ms
# Warmup Iteration   2: 6.406 ops/ms
# Warmup Iteration   3: 8.442 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 8.433 ops/ms
Iteration   3: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.205 ±(99.9%) 3.883 ops/ms [Average]
  (min, avg, max) = (8.011, 8.205, 8.433), stdev = 0.213
  CI (99.9%): [4.322, 12.087] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.143 ops/ms
# Warmup Iteration   2: 6.189 ops/ms
# Warmup Iteration   3: 7.794 ops/ms
Iteration   1: 7.715 ops/ms
Iteration   2: 7.456 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.749 ±(99.9%) 5.677 ops/ms [Average]
  (min, avg, max) = (7.456, 7.749, 8.076), stdev = 0.311
  CI (99.9%): [2.072, 13.426] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.979 ops/ms
# Warmup Iteration   2: 5.030 ops/ms
# Warmup Iteration   3: 6.060 ops/ms
Iteration   1: 6.604 ops/ms
Iteration   2: 6.591 ops/ms
Iteration   3: 6.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.559 ±(99.9%) 1.228 ops/ms [Average]
  (min, avg, max) = (6.481, 6.559, 6.604), stdev = 0.067
  CI (99.9%): [5.330, 7.787] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.612 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.895 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.399 ±(99.9%) 0.007 ms/op
Iteration   1: 4.024 ±(99.9%) 0.006 ms/op
Iteration   2: 4.011 ±(99.9%) 0.008 ms/op
Iteration   3: 4.024 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.020 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (4.011, 4.020, 4.024), stdev = 0.008
  CI (99.9%): [3.877, 4.163] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.053 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.007 ms/op
Iteration   1: 3.882 ±(99.9%) 0.005 ms/op
Iteration   2: 3.975 ±(99.9%) 0.003 ms/op
Iteration   3: 3.984 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.947 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.882, 3.947, 3.984), stdev = 0.056
  CI (99.9%): [2.922, 4.972] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.369 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.865 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.008 ms/op
Iteration   1: 4.106 ±(99.9%) 0.006 ms/op
Iteration   2: 4.013 ±(99.9%) 0.009 ms/op
Iteration   3: 4.091 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.070 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (4.013, 4.070, 4.106), stdev = 0.050
  CI (99.9%): [3.166, 4.974] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.669 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.532 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.013 ms/op
Iteration   1: 4.765 ±(99.9%) 0.011 ms/op
Iteration   2: 4.848 ±(99.9%) 0.016 ms/op
Iteration   3: 4.796 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.803 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (4.765, 4.803, 4.848), stdev = 0.042
  CI (99.9%): [4.037, 5.568] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.336 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.190 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.582 ±(99.9%) 0.020 ms/op
Iteration   1: 4.147 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  26.571 ms/op
                 createUser·p0.9999: 30.451 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   2: 4.010 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  15.050 ms/op
                 createUser·p0.9999: 28.083 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   3: 4.208 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  29.721 ms/op
                 createUser·p0.9999: 32.768 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232927
  mean =      4.120 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 447 
    [ 2.500,  5.000) = 214003 
    [ 5.000,  7.500) = 15265 
    [ 7.500, 10.000) = 2097 
    [10.000, 12.500) = 630 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 80 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     26.020 ms/op
     p(99.9900) =     31.864 ms/op
     p(99.9990) =     33.874 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 12.682 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 5.018 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.014 ms/op
Iteration   1: 4.050 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  12.137 ms/op
                 existUser·p0.9999: 26.751 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   2: 4.120 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.977 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   8.249 ms/op
                 existUser·p0.999:  27.034 ms/op
                 existUser·p0.9999: 33.701 ms/op
                 existUser·p1.00:   34.144 ms/op

Iteration   3: 4.252 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   6.390 ms/op
                 existUser·p0.99:   9.028 ms/op
                 existUser·p0.999:  15.778 ms/op
                 existUser·p0.9999: 35.486 ms/op
                 existUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 231898
  mean =      4.139 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184 
    [ 2.500,  5.000) = 212362 
    [ 5.000,  7.500) = 15536 
    [ 7.500, 10.000) = 2660 
    [10.000, 12.500) = 707 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     17.632 ms/op
     p(99.9900) =     34.328 ms/op
     p(99.9990) =     36.614 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 14.284 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.219 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.175 ±(99.9%) 0.015 ms/op
Iteration   1: 4.342 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.833 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   6.250 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  24.248 ms/op
                 getUser·p0.9999: 33.543 ms/op
                 getUser·p1.00:   39.256 ms/op

Iteration   2: 4.043 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.650 ms/op
                 getUser·p0.999:  26.473 ms/op
                 getUser·p0.9999: 33.262 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   3: 4.103 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  11.601 ms/op
                 getUser·p0.9999: 31.641 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230642
  mean =      4.159 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 211761 
    [ 5.000,  7.500) = 15536 
    [ 7.500, 10.000) = 2281 
    [10.000, 12.500) = 633 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 65 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     24.445 ms/op
     p(99.9900) =     32.735 ms/op
     p(99.9990) =     39.216 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


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
# Warmup Iteration   1: 15.542 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 6.039 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.920 ±(99.9%) 0.018 ms/op
Iteration   1: 5.053 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   7.662 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  25.100 ms/op
                 listUser·p0.9999: 28.902 ms/op
                 listUser·p1.00:   29.622 ms/op

Iteration   2: 4.756 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  20.251 ms/op
                 listUser·p0.9999: 28.615 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   3: 4.758 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 19.309 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197882
  mean =      4.852 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 156376 
    [ 5.000,  7.500) = 34641 
    [ 7.500, 10.000) = 4768 
    [10.000, 12.500) = 1252 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.833 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.373 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     20.189 ms/op
     p(99.9900) =     28.482 ms/op
     p(99.9990) =     30.649 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.769 ± 6.488  ops/ms
ClientPb.existUser                       thrpt       3   8.205 ± 3.883  ops/ms
ClientPb.getUser                         thrpt       3   7.749 ± 5.677  ops/ms
ClientPb.listUser                        thrpt       3   6.559 ± 1.228  ops/ms
ClientPb.createUser                       avgt       3   4.020 ± 0.143   ms/op
ClientPb.existUser                        avgt       3   3.947 ± 1.025   ms/op
ClientPb.getUser                          avgt       3   4.070 ± 0.904   ms/op
ClientPb.listUser                         avgt       3   4.803 ± 0.766   ms/op
ClientPb.createUser                     sample  232927   4.120 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.440           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.020           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.864           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  231898   4.139 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.589           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.620           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.380           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.632           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.328           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.962           ms/op
ClientPb.getUser                        sample  230642   4.159 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.454           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.445           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.735           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.256           ms/op
ClientPb.listUser                       sample  197882   4.852 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.373           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.191           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.482           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.162           ms/op
