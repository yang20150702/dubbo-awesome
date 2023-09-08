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
# Warmup Iteration   1: 1.082 ops/ms
# Warmup Iteration   2: 2.179 ops/ms
# Warmup Iteration   3: 5.044 ops/ms
Iteration   1: 5.287 ops/ms
Iteration   2: 5.377 ops/ms
Iteration   3: 5.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.384 ±(99.9%) 1.828 ops/ms [Average]
  (min, avg, max) = (5.287, 5.384, 5.487), stdev = 0.100
  CI (99.9%): [3.555, 7.212] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.679 ops/ms
# Warmup Iteration   2: 4.789 ops/ms
# Warmup Iteration   3: 5.926 ops/ms
Iteration   1: 5.875 ops/ms
Iteration   2: 5.784 ops/ms
Iteration   3: 5.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.837 ±(99.9%) 0.865 ops/ms [Average]
  (min, avg, max) = (5.784, 5.837, 5.875), stdev = 0.047
  CI (99.9%): [4.971, 6.702] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.417 ops/ms
# Warmup Iteration   2: 4.146 ops/ms
# Warmup Iteration   3: 5.306 ops/ms
Iteration   1: 5.379 ops/ms
Iteration   2: 5.675 ops/ms
Iteration   3: 5.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.592 ±(99.9%) 3.408 ops/ms [Average]
  (min, avg, max) = (5.379, 5.592, 5.724), stdev = 0.187
  CI (99.9%): [2.185, 9.000] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.378 ops/ms
# Warmup Iteration   2: 3.791 ops/ms
# Warmup Iteration   3: 4.890 ops/ms
Iteration   1: 4.758 ops/ms
Iteration   2: 4.995 ops/ms
Iteration   3: 4.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.865 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (4.758, 4.865, 4.995), stdev = 0.121
  CI (99.9%): [2.667, 7.063] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.268 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 7.635 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.258 ±(99.9%) 0.010 ms/op
Iteration   1: 5.819 ±(99.9%) 0.015 ms/op
Iteration   2: 5.820 ±(99.9%) 0.015 ms/op
Iteration   3: 5.837 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.825 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (5.819, 5.825, 5.837), stdev = 0.010
  CI (99.9%): [5.645, 6.005] (assumes normal distribution)


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
# Warmup Iteration   1: 16.899 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.691 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.780 ±(99.9%) 0.008 ms/op
Iteration   1: 5.517 ±(99.9%) 0.007 ms/op
Iteration   2: 5.558 ±(99.9%) 0.009 ms/op
Iteration   3: 5.611 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.562 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (5.517, 5.562, 5.611), stdev = 0.047
  CI (99.9%): [4.704, 6.420] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.413 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.363 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.781 ±(99.9%) 0.011 ms/op
Iteration   1: 5.669 ±(99.9%) 0.019 ms/op
Iteration   2: 5.874 ±(99.9%) 0.007 ms/op
Iteration   3: 5.808 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.784 ±(99.9%) 1.904 ms/op [Average]
  (min, avg, max) = (5.669, 5.784, 5.874), stdev = 0.104
  CI (99.9%): [3.879, 7.688] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.562 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 8.575 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.894 ±(99.9%) 0.016 ms/op
Iteration   1: 6.869 ±(99.9%) 0.014 ms/op
Iteration   2: 6.630 ±(99.9%) 0.014 ms/op
Iteration   3: 6.441 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.647 ±(99.9%) 3.910 ms/op [Average]
  (min, avg, max) = (6.441, 6.647, 6.869), stdev = 0.214
  CI (99.9%): [2.737, 10.557] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.947 ±(99.9%) 0.374 ms/op
# Warmup Iteration   2: 7.616 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.714 ±(99.9%) 0.038 ms/op
Iteration   1: 5.848 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.716 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.733 ms/op
                 createUser·p0.95:   9.159 ms/op
                 createUser·p0.99:   11.698 ms/op
                 createUser·p0.999:  25.840 ms/op
                 createUser·p0.9999: 30.297 ms/op
                 createUser·p1.00:   32.080 ms/op

Iteration   2: 5.798 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.367 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   7.569 ms/op
                 createUser·p0.95:   8.618 ms/op
                 createUser·p0.99:   12.124 ms/op
                 createUser·p0.999:  28.338 ms/op
                 createUser·p0.9999: 35.652 ms/op
                 createUser·p1.00:   36.110 ms/op

Iteration   3: 5.945 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.556 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.528 ms/op
                 createUser·p0.95:   8.733 ms/op
                 createUser·p0.99:   12.759 ms/op
                 createUser·p0.999:  33.009 ms/op
                 createUser·p0.9999: 37.814 ms/op
                 createUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163637
  mean =      5.863 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 42440 
    [ 5.000,  7.500) = 103719 
    [ 7.500, 10.000) = 13147 
    [10.000, 12.500) = 2941 
    [12.500, 15.000) = 897 
    [15.000, 17.500) = 238 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 46 
    [35.000, 37.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.864 ms/op
     p(99.0000) =     12.173 ms/op
     p(99.9000) =     29.032 ms/op
     p(99.9900) =     36.218 ms/op
     p(99.9990) =     38.464 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.279 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 6.485 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.749 ±(99.9%) 0.025 ms/op
Iteration   1: 5.560 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   7.242 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  16.744 ms/op
                 existUser·p0.9999: 27.075 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   2: 5.498 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.939 ms/op
                 existUser·p0.95:   8.004 ms/op
                 existUser·p0.99:   11.796 ms/op
                 existUser·p0.999:  26.542 ms/op
                 existUser·p0.9999: 30.376 ms/op
                 existUser·p1.00:   30.638 ms/op

Iteration   3: 5.546 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.467 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   7.266 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   11.715 ms/op
                 existUser·p0.999:  31.523 ms/op
                 existUser·p0.9999: 35.929 ms/op
                 existUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173398
  mean =      5.535 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 78042 
    [ 5.000,  7.500) = 81213 
    [ 7.500, 10.000) = 10518 
    [10.000, 12.500) = 2560 
    [12.500, 15.000) = 671 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      8.315 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     34.666 ms/op
     p(99.9990) =     37.831 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.768 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.712 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.879 ±(99.9%) 0.024 ms/op
Iteration   1: 5.620 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.114 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   7.168 ms/op
                 getUser·p0.95:   8.454 ms/op
                 getUser·p0.99:   12.042 ms/op
                 getUser·p0.999:  26.357 ms/op
                 getUser·p0.9999: 29.501 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   2: 5.945 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.544 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   7.832 ms/op
                 getUser·p0.95:   9.667 ms/op
                 getUser·p0.99:   13.801 ms/op
                 getUser·p0.999:  28.711 ms/op
                 getUser·p0.9999: 34.988 ms/op
                 getUser·p1.00:   45.548 ms/op

Iteration   3: 5.740 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   7.373 ms/op
                 getUser·p0.95:   8.946 ms/op
                 getUser·p0.99:   12.091 ms/op
                 getUser·p0.999:  28.190 ms/op
                 getUser·p0.9999: 31.373 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166370
  mean =      5.765 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 54428 
    [ 5.000, 10.000) = 106765 
    [10.000, 15.000) = 4419 
    [15.000, 20.000) = 502 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 159 
    [30.000, 35.000) = 46 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.422 ms/op
     p(95.0000) =      9.028 ms/op
     p(99.0000) =     12.583 ms/op
     p(99.9000) =     27.525 ms/op
     p(99.9900) =     31.448 ms/op
     p(99.9990) =     45.461 ms/op
     p(99.9999) =     45.548 ms/op
    p(100.0000) =     45.548 ms/op


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
# Warmup Iteration   1: 20.031 ±(99.9%) 0.403 ms/op
# Warmup Iteration   2: 7.953 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.824 ±(99.9%) 0.031 ms/op
Iteration   1: 6.636 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.200 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  29.837 ms/op
                 listUser·p0.9999: 38.362 ms/op
                 listUser·p1.00:   39.256 ms/op

Iteration   2: 6.826 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   10.371 ms/op
                 listUser·p0.99:   14.713 ms/op
                 listUser·p0.999:  32.866 ms/op
                 listUser·p0.9999: 37.731 ms/op
                 listUser·p1.00:   39.911 ms/op

Iteration   3: 6.833 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   10.338 ms/op
                 listUser·p0.99:   13.817 ms/op
                 listUser·p0.999:  23.888 ms/op
                 listUser·p0.9999: 38.620 ms/op
                 listUser·p1.00:   39.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141824
  mean =      6.764 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 3893 
    [ 5.000,  7.500) = 113434 
    [ 7.500, 10.000) = 16893 
    [10.000, 12.500) = 5299 
    [12.500, 15.000) = 1238 
    [15.000, 17.500) = 445 
    [17.500, 20.000) = 234 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 57 
    [35.000, 37.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      6.250 ms/op
     p(90.0000) =      8.536 ms/op
     p(95.0000) =     10.174 ms/op
     p(99.0000) =     13.713 ms/op
     p(99.9000) =     31.731 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     39.829 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.384 ± 1.828  ops/ms
ClientPb.existUser                       thrpt       3   5.837 ± 0.865  ops/ms
ClientPb.getUser                         thrpt       3   5.592 ± 3.408  ops/ms
ClientPb.listUser                        thrpt       3   4.865 ± 2.198  ops/ms
ClientPb.createUser                       avgt       3   5.825 ± 0.180   ms/op
ClientPb.existUser                        avgt       3   5.562 ± 0.858   ms/op
ClientPb.getUser                          avgt       3   5.784 ± 1.904   ms/op
ClientPb.listUser                         avgt       3   6.647 ± 3.910   ms/op
ClientPb.createUser                     sample  163637   5.863 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.367           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.864           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.173           ms/op
ClientPb.createUser:createUser·p0.999   sample          29.032           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.218           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.797           ms/op
ClientPb.existUser                      sample  173398   5.535 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.467           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.087           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.143           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.315           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.583           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.612           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.666           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.601           ms/op
ClientPb.getUser                        sample  166370   5.765 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.114           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.308           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.028           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.583           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.525           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.448           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.548           ms/op
ClientPb.listUser                       sample  141824   6.764 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.569           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.250           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.174           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.713           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.731           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.339           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.911           ms/op
