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
# Warmup Iteration   1: 1.088 ops/ms
# Warmup Iteration   2: 2.642 ops/ms
# Warmup Iteration   3: 5.692 ops/ms
Iteration   1: 6.216 ops/ms
Iteration   2: 6.186 ops/ms
Iteration   3: 6.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.265 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (6.186, 6.265, 6.392), stdev = 0.111
  CI (99.9%): [4.232, 8.298] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.595 ops/ms
# Warmup Iteration   2: 5.101 ops/ms
# Warmup Iteration   3: 6.136 ops/ms
Iteration   1: 6.603 ops/ms
Iteration   2: 6.758 ops/ms
Iteration   3: 6.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.640 ±(99.9%) 1.918 ops/ms [Average]
  (min, avg, max) = (6.558, 6.640, 6.758), stdev = 0.105
  CI (99.9%): [4.721, 8.558] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.008 ops/ms
# Warmup Iteration   2: 5.059 ops/ms
# Warmup Iteration   3: 6.449 ops/ms
Iteration   1: 6.519 ops/ms
Iteration   2: 6.481 ops/ms
Iteration   3: 6.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.519 ±(99.9%) 0.686 ops/ms [Average]
  (min, avg, max) = (6.481, 6.519, 6.557), stdev = 0.038
  CI (99.9%): [5.833, 7.205] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 1.801 ops/ms
# Warmup Iteration   2: 4.940 ops/ms
# Warmup Iteration   3: 5.506 ops/ms
Iteration   1: 5.503 ops/ms
Iteration   2: 5.701 ops/ms
Iteration   3: 5.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.589 ±(99.9%) 1.849 ops/ms [Average]
  (min, avg, max) = (5.503, 5.589, 5.701), stdev = 0.101
  CI (99.9%): [3.739, 7.438] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.554 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.449 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.240 ±(99.9%) 0.010 ms/op
Iteration   1: 5.070 ±(99.9%) 0.013 ms/op
Iteration   2: 5.285 ±(99.9%) 0.009 ms/op
Iteration   3: 5.193 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.183 ±(99.9%) 1.962 ms/op [Average]
  (min, avg, max) = (5.070, 5.183, 5.285), stdev = 0.108
  CI (99.9%): [3.220, 7.145] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 15.540 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.738 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.080 ±(99.9%) 0.012 ms/op
Iteration   1: 4.795 ±(99.9%) 0.013 ms/op
Iteration   2: 4.939 ±(99.9%) 0.014 ms/op
Iteration   3: 4.999 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.911 ±(99.9%) 1.918 ms/op [Average]
  (min, avg, max) = (4.795, 4.911, 4.999), stdev = 0.105
  CI (99.9%): [2.993, 6.829] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.714 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.113 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.358 ±(99.9%) 0.012 ms/op
Iteration   1: 5.288 ±(99.9%) 0.007 ms/op
Iteration   2: 5.149 ±(99.9%) 0.008 ms/op
Iteration   3: 4.992 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.143 ±(99.9%) 2.704 ms/op [Average]
  (min, avg, max) = (4.992, 5.143, 5.288), stdev = 0.148
  CI (99.9%): [2.439, 7.846] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 17.661 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 7.012 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.845 ±(99.9%) 0.017 ms/op
Iteration   1: 5.502 ±(99.9%) 0.020 ms/op
Iteration   2: 5.571 ±(99.9%) 0.012 ms/op
Iteration   3: 5.569 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.547 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (5.502, 5.547, 5.571), stdev = 0.039
  CI (99.9%): [4.832, 6.263] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.572 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 6.260 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.307 ±(99.9%) 0.022 ms/op
Iteration   1: 4.901 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   6.078 ms/op
                 createUser·p0.95:   7.274 ms/op
                 createUser·p0.99:   9.950 ms/op
                 createUser·p0.999:  14.793 ms/op
                 createUser·p0.9999: 23.543 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   2: 4.857 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   8.844 ms/op
                 createUser·p0.999:  24.642 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   3: 5.223 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   7.004 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  24.417 ms/op
                 createUser·p0.9999: 29.844 ms/op
                 createUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 192231
  mean =      4.988 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 125425 
    [ 5.000,  7.500) = 60232 
    [ 7.500, 10.000) = 4925 
    [10.000, 12.500) = 969 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      6.889 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     22.562 ms/op
     p(99.9900) =     28.421 ms/op
     p(99.9990) =     30.926 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.624 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.188 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.053 ±(99.9%) 0.017 ms/op
Iteration   1: 4.843 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.898 ms/op
                 existUser·p0.99:   9.609 ms/op
                 existUser·p0.999:  18.548 ms/op
                 existUser·p0.9999: 26.785 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 4.822 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.833 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.668 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  20.972 ms/op
                 existUser·p0.9999: 29.834 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   3: 4.898 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.909 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.644 ms/op
                 existUser·p0.99:   9.912 ms/op
                 existUser·p0.999:  22.552 ms/op
                 existUser·p0.9999: 28.310 ms/op
                 existUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 197555
  mean =      4.854 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 149190 
    [ 5.000,  7.500) = 42112 
    [ 7.500, 10.000) = 4396 
    [10.000, 12.500) = 915 
    [12.500, 15.000) = 523 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     30.187 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.097 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.914 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.186 ±(99.9%) 0.016 ms/op
Iteration   1: 4.912 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   5.849 ms/op
                 getUser·p0.95:   6.873 ms/op
                 getUser·p0.99:   9.814 ms/op
                 getUser·p0.999:  24.019 ms/op
                 getUser·p0.9999: 36.405 ms/op
                 getUser·p1.00:   36.569 ms/op

Iteration   2: 4.965 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   4.760 ms/op
                 getUser·p0.90:   5.734 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  22.797 ms/op
                 getUser·p0.9999: 28.479 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 5.091 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.023 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.639 ms/op
                 getUser·p0.99:   9.994 ms/op
                 getUser·p0.999:  16.648 ms/op
                 getUser·p0.9999: 29.203 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192369
  mean =      4.988 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 132189 
    [ 5.000,  7.500) = 52954 
    [ 7.500, 10.000) = 5634 
    [10.000, 12.500) = 894 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.925 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      7.111 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     22.692 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.286 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 7.920 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.229 ±(99.9%) 0.023 ms/op
Iteration   1: 6.057 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.666 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   11.091 ms/op
                 listUser·p0.999:  26.378 ms/op
                 listUser·p0.9999: 30.435 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 5.674 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   6.406 ms/op
                 listUser·p0.95:   7.102 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  25.264 ms/op
                 listUser·p0.9999: 33.054 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   3: 5.791 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   10.474 ms/op
                 listUser·p0.999:  24.216 ms/op
                 listUser·p0.9999: 26.181 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164321
  mean =      5.837 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 20374 
    [ 5.000,  7.500) = 134672 
    [ 7.500, 10.000) = 6958 
    [10.000, 12.500) = 1553 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.519 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     25.123 ms/op
     p(99.9900) =     31.944 ms/op
     p(99.9990) =     33.961 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.265 ± 2.033  ops/ms
ClientPb.existUser                       thrpt       3   6.640 ± 1.918  ops/ms
ClientPb.getUser                         thrpt       3   6.519 ± 0.686  ops/ms
ClientPb.listUser                        thrpt       3   5.589 ± 1.849  ops/ms
ClientPb.createUser                       avgt       3   5.183 ± 1.962   ms/op
ClientPb.existUser                        avgt       3   4.911 ± 1.918   ms/op
ClientPb.getUser                          avgt       3   5.143 ± 2.704   ms/op
ClientPb.listUser                         avgt       3   5.547 ± 0.715   ms/op
ClientPb.createUser                     sample  192231   4.988 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.889           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.634           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.562           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.421           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.228           ms/op
ClientPb.existUser                      sample  197555   4.854 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.686           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.716           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.972           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.803           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474           ms/op
ClientPb.getUser                        sample  192369   4.988 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.925           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.617           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.692           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.867           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.569           ms/op
ClientPb.listUser                       sample  164321   5.837 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.519           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.734           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.725           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.682           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.123           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.944           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.341           ms/op
