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
# Warmup Iteration   1: 1.167 ops/ms
# Warmup Iteration   2: 2.419 ops/ms
# Warmup Iteration   3: 5.295 ops/ms
Iteration   1: 5.846 ops/ms
Iteration   2: 6.028 ops/ms
Iteration   3: 5.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.955 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (5.846, 5.955, 6.028), stdev = 0.096
  CI (99.9%): [4.204, 7.706] (assumes normal distribution)


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
# Warmup Iteration   1: 1.733 ops/ms
# Warmup Iteration   2: 5.443 ops/ms
# Warmup Iteration   3: 6.221 ops/ms
Iteration   1: 6.346 ops/ms
Iteration   2: 6.306 ops/ms
Iteration   3: 6.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.295 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (6.231, 6.295, 6.346), stdev = 0.058
  CI (99.9%): [5.231, 7.358] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.647 ops/ms
# Warmup Iteration   2: 4.661 ops/ms
# Warmup Iteration   3: 5.946 ops/ms
Iteration   1: 6.062 ops/ms
Iteration   2: 5.709 ops/ms
Iteration   3: 6.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.943 ±(99.9%) 3.707 ops/ms [Average]
  (min, avg, max) = (5.709, 5.943, 6.062), stdev = 0.203
  CI (99.9%): [2.237, 9.650] (assumes normal distribution)


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
# Warmup Iteration   1: 1.504 ops/ms
# Warmup Iteration   2: 4.391 ops/ms
# Warmup Iteration   3: 5.300 ops/ms
Iteration   1: 5.424 ops/ms
Iteration   2: 5.474 ops/ms
Iteration   3: 5.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.487 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (5.424, 5.487, 5.562), stdev = 0.070
  CI (99.9%): [4.216, 6.757] (assumes normal distribution)


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
# Warmup Iteration   1: 17.889 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.964 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.230 ±(99.9%) 0.012 ms/op
Iteration   1: 5.058 ±(99.9%) 0.015 ms/op
Iteration   2: 5.060 ±(99.9%) 0.018 ms/op
Iteration   3: 5.056 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.058 ±(99.9%) 0.032 ms/op [Average]
  (min, avg, max) = (5.056, 5.058, 5.060), stdev = 0.002
  CI (99.9%): [5.026, 5.090] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.917 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.320 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.168 ±(99.9%) 0.007 ms/op
Iteration   1: 4.902 ±(99.9%) 0.011 ms/op
Iteration   2: 4.664 ±(99.9%) 0.024 ms/op
Iteration   3: 4.798 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.788 ±(99.9%) 2.178 ms/op [Average]
  (min, avg, max) = (4.664, 4.788, 4.902), stdev = 0.119
  CI (99.9%): [2.610, 6.966] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.601 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.624 ±(99.9%) 0.010 ms/op
Iteration   1: 5.241 ±(99.9%) 0.007 ms/op
Iteration   2: 5.180 ±(99.9%) 0.009 ms/op
Iteration   3: 5.129 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.184 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (5.129, 5.184, 5.241), stdev = 0.056
  CI (99.9%): [4.163, 6.204] (assumes normal distribution)


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
# Warmup Iteration   1: 18.841 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 7.210 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.787 ±(99.9%) 0.018 ms/op
Iteration   1: 5.769 ±(99.9%) 0.015 ms/op
Iteration   2: 5.877 ±(99.9%) 0.021 ms/op
Iteration   3: 5.829 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.825 ±(99.9%) 0.995 ms/op [Average]
  (min, avg, max) = (5.769, 5.825, 5.877), stdev = 0.055
  CI (99.9%): [4.830, 6.819] (assumes normal distribution)


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
# Warmup Iteration   1: 18.882 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.355 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.565 ±(99.9%) 0.026 ms/op
Iteration   1: 5.372 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.118 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   7.815 ms/op
                 createUser·p0.99:   10.437 ms/op
                 createUser·p0.999:  22.215 ms/op
                 createUser·p0.9999: 29.231 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   2: 5.197 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.109 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   6.914 ms/op
                 createUser·p0.99:   10.043 ms/op
                 createUser·p0.999:  23.322 ms/op
                 createUser·p0.9999: 25.783 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   3: 5.101 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.017 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.283 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  24.341 ms/op
                 createUser·p0.9999: 28.908 ms/op
                 createUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 183746
  mean =      5.221 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 99082 
    [ 5.000,  7.500) = 76828 
    [ 7.500, 10.000) = 6071 
    [10.000, 12.500) = 1066 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      2.017 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.439 ms/op
     p(95.0000) =      7.291 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     22.332 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     29.890 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 15.242 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.250 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.053 ±(99.9%) 0.017 ms/op
Iteration   1: 4.969 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.302 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.087 ms/op
                 existUser·p0.95:   6.745 ms/op
                 existUser·p0.99:   9.339 ms/op
                 existUser·p0.999:  20.605 ms/op
                 existUser·p0.9999: 30.460 ms/op
                 existUser·p1.00:   32.080 ms/op

Iteration   2: 4.978 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   4.653 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   6.922 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  25.721 ms/op
                 existUser·p0.9999: 31.888 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   3: 4.965 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   6.922 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  23.160 ms/op
                 existUser·p0.9999: 27.136 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 192969
  mean =      4.971 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 132286 
    [ 5.000,  7.500) = 54426 
    [ 7.500, 10.000) = 4626 
    [10.000, 12.500) = 881 
    [12.500, 15.000) = 317 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     21.925 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     32.417 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 17.100 ±(99.9%) 0.311 ms/op
# Warmup Iteration   2: 5.943 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.405 ±(99.9%) 0.017 ms/op
Iteration   1: 5.196 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.079 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.300 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   10.027 ms/op
                 getUser·p0.999:  24.166 ms/op
                 getUser·p0.9999: 31.531 ms/op
                 getUser·p1.00:   32.342 ms/op

Iteration   2: 5.156 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   4.841 ms/op
                 getUser·p0.90:   6.218 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  25.362 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   3: 5.169 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.609 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.185 ms/op
                 getUser·p0.95:   7.086 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  25.836 ms/op
                 getUser·p0.9999: 30.883 ms/op
                 getUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185469
  mean =      5.174 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 107976 
    [ 5.000,  7.500) = 69930 
    [ 7.500, 10.000) = 5723 
    [10.000, 12.500) = 1207 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     25.231 ms/op
     p(99.9900) =     30.668 ms/op
     p(99.9990) =     32.090 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 19.423 ±(99.9%) 0.345 ms/op
# Warmup Iteration   2: 7.012 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.021 ±(99.9%) 0.022 ms/op
Iteration   1: 5.978 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   5.579 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  25.792 ms/op
                 listUser·p0.9999: 36.546 ms/op
                 listUser·p1.00:   36.897 ms/op

Iteration   2: 5.728 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.528 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   6.889 ms/op
                 listUser·p0.95:   7.905 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  25.378 ms/op
                 listUser·p0.9999: 28.437 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   3: 5.811 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   6.824 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  19.985 ms/op
                 listUser·p0.9999: 27.607 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164427
  mean =      5.837 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 19521 
    [ 5.000,  7.500) = 133599 
    [ 7.500, 10.000) = 8793 
    [10.000, 12.500) = 1612 
    [12.500, 15.000) = 398 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      8.053 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     24.955 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     36.770 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.955 ± 1.751  ops/ms
ClientPb.existUser                       thrpt       3   6.295 ± 1.064  ops/ms
ClientPb.getUser                         thrpt       3   5.943 ± 3.707  ops/ms
ClientPb.listUser                        thrpt       3   5.487 ± 1.270  ops/ms
ClientPb.createUser                       avgt       3   5.058 ± 0.032   ms/op
ClientPb.existUser                        avgt       3   4.788 ± 2.178   ms/op
ClientPb.getUser                          avgt       3   5.184 ± 1.020   ms/op
ClientPb.listUser                         avgt       3   5.825 ± 0.995   ms/op
ClientPb.createUser                     sample  183746   5.221 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.017           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.932           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.439           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.291           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.830           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.332           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.443           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.917           ms/op
ClientPb.existUser                      sample  192969   4.971 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.873           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.519           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.925           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.130           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  185469   5.174 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.884           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.978           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.231           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.668           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  164427   5.837 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.053           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.895           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.955           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.783           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.897           ms/op
