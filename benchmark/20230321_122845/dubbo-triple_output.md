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
# Warmup Iteration   1: 1.242 ops/ms
# Warmup Iteration   2: 2.930 ops/ms
# Warmup Iteration   3: 6.067 ops/ms
Iteration   1: 6.069 ops/ms
Iteration   2: 6.513 ops/ms
Iteration   3: 6.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.330 ±(99.9%) 4.237 ops/ms [Average]
  (min, avg, max) = (6.069, 6.330, 6.513), stdev = 0.232
  CI (99.9%): [2.092, 10.567] (assumes normal distribution)


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
# Warmup Iteration   1: 1.861 ops/ms
# Warmup Iteration   2: 5.630 ops/ms
# Warmup Iteration   3: 6.548 ops/ms
Iteration   1: 6.547 ops/ms
Iteration   2: 6.811 ops/ms
Iteration   3: 6.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.687 ±(99.9%) 2.424 ops/ms [Average]
  (min, avg, max) = (6.547, 6.687, 6.811), stdev = 0.133
  CI (99.9%): [4.263, 9.111] (assumes normal distribution)


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
# Warmup Iteration   1: 1.924 ops/ms
# Warmup Iteration   2: 5.417 ops/ms
# Warmup Iteration   3: 6.247 ops/ms
Iteration   1: 6.439 ops/ms
Iteration   2: 6.328 ops/ms
Iteration   3: 6.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.407 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (6.328, 6.407, 6.453), stdev = 0.068
  CI (99.9%): [5.161, 7.652] (assumes normal distribution)


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
# Warmup Iteration   1: 1.851 ops/ms
# Warmup Iteration   2: 4.779 ops/ms
# Warmup Iteration   3: 5.401 ops/ms
Iteration   1: 5.509 ops/ms
Iteration   2: 5.461 ops/ms
Iteration   3: 5.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.534 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (5.461, 5.534, 5.633), stdev = 0.089
  CI (99.9%): [3.913, 7.156] (assumes normal distribution)


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
# Warmup Iteration   1: 15.031 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.522 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.184 ±(99.9%) 0.010 ms/op
Iteration   1: 4.785 ±(99.9%) 0.022 ms/op
Iteration   2: 4.847 ±(99.9%) 0.013 ms/op
Iteration   3: 4.924 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.852 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (4.785, 4.852, 4.924), stdev = 0.069
  CI (99.9%): [3.585, 6.118] (assumes normal distribution)


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
# Warmup Iteration   1: 14.668 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.374 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.868 ±(99.9%) 0.011 ms/op
Iteration   1: 4.639 ±(99.9%) 0.022 ms/op
Iteration   2: 4.617 ±(99.9%) 0.017 ms/op
Iteration   3: 4.677 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.644 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (4.617, 4.644, 4.677), stdev = 0.030
  CI (99.9%): [4.092, 5.196] (assumes normal distribution)


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
# Warmup Iteration   1: 16.105 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.794 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.813 ±(99.9%) 0.014 ms/op
Iteration   1: 5.111 ±(99.9%) 0.009 ms/op
Iteration   2: 4.951 ±(99.9%) 0.010 ms/op
Iteration   3: 4.983 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.015 ±(99.9%) 1.542 ms/op [Average]
  (min, avg, max) = (4.951, 5.015, 5.111), stdev = 0.085
  CI (99.9%): [3.473, 6.557] (assumes normal distribution)


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
# Warmup Iteration   1: 16.466 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.750 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.036 ±(99.9%) 0.008 ms/op
Iteration   1: 5.801 ±(99.9%) 0.011 ms/op
Iteration   2: 5.736 ±(99.9%) 0.013 ms/op
Iteration   3: 5.809 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.782 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (5.736, 5.782, 5.809), stdev = 0.040
  CI (99.9%): [5.047, 6.517] (assumes normal distribution)


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
# Warmup Iteration   1: 15.656 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.832 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.086 ±(99.9%) 0.018 ms/op
Iteration   1: 4.925 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.122 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   5.939 ms/op
                 createUser·p0.95:   6.693 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  19.185 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 5.068 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   6.988 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  25.372 ms/op
                 createUser·p0.9999: 28.959 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 4.962 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.101 ms/op
                 createUser·p0.50:   4.727 ms/op
                 createUser·p0.90:   5.939 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  23.359 ms/op
                 createUser·p0.9999: 31.818 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 192496
  mean =      4.984 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 122452 
    [ 5.000,  7.500) = 63850 
    [ 7.500, 10.000) = 4852 
    [10.000, 12.500) = 749 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     21.110 ms/op
     p(99.9900) =     31.547 ms/op
     p(99.9990) =     32.034 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 13.570 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.450 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.811 ±(99.9%) 0.015 ms/op
Iteration   1: 4.672 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.521 ms/op
                 existUser·p0.95:   6.095 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  15.537 ms/op
                 existUser·p0.9999: 24.089 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 4.756 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.414 ms/op
                 existUser·p0.99:   8.946 ms/op
                 existUser·p0.999:  17.503 ms/op
                 existUser·p0.9999: 24.233 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 4.731 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.775 ms/op
                 existUser·p0.95:   6.537 ms/op
                 existUser·p0.99:   8.887 ms/op
                 existUser·p0.999:  16.295 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 203414
  mean =      4.719 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 153875 
    [ 5.000,  7.500) = 45091 
    [ 7.500, 10.000) = 3207 
    [10.000, 12.500) = 603 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     17.307 ms/op
     p(99.9900) =     24.554 ms/op
     p(99.9990) =     26.474 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 14.485 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 5.402 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.181 ±(99.9%) 0.018 ms/op
Iteration   1: 5.039 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   6.349 ms/op
                 getUser·p0.95:   7.504 ms/op
                 getUser·p0.99:   11.551 ms/op
                 getUser·p0.999:  20.733 ms/op
                 getUser·p0.9999: 29.338 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   2: 4.949 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.013 ms/op
                 getUser·p0.50:   4.669 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   6.955 ms/op
                 getUser·p0.99:   10.748 ms/op
                 getUser·p0.999:  22.741 ms/op
                 getUser·p0.9999: 26.887 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 5.079 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.200 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   7.086 ms/op
                 getUser·p0.99:   9.912 ms/op
                 getUser·p0.999:  23.500 ms/op
                 getUser·p0.9999: 30.989 ms/op
                 getUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 190994
  mean =      5.022 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 123732 
    [ 5.000,  7.500) = 58925 
    [ 7.500, 10.000) = 5736 
    [10.000, 12.500) = 1565 
    [12.500, 15.000) = 580 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.013 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      7.209 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     29.354 ms/op
     p(99.9990) =     31.591 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 15.182 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 6.416 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.065 ±(99.9%) 0.024 ms/op
Iteration   1: 5.822 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.941 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.700 ms/op
                 listUser·p0.999:  29.460 ms/op
                 listUser·p0.9999: 33.571 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   2: 5.756 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.002 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   6.750 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  23.116 ms/op
                 listUser·p0.9999: 32.546 ms/op
                 listUser·p1.00:   36.438 ms/op

Iteration   3: 5.513 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.193 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  18.285 ms/op
                 listUser·p0.9999: 21.371 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 168541
  mean =      5.694 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 38110 
    [ 5.000,  7.500) = 121817 
    [ 7.500, 10.000) = 6420 
    [10.000, 12.500) = 1434 
    [12.500, 15.000) = 317 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     23.658 ms/op
     p(99.9900) =     32.478 ms/op
     p(99.9990) =     35.944 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.330 ± 4.237  ops/ms
ClientPb.existUser                       thrpt       3   6.687 ± 2.424  ops/ms
ClientPb.getUser                         thrpt       3   6.407 ± 1.245  ops/ms
ClientPb.listUser                        thrpt       3   5.534 ± 1.622  ops/ms
ClientPb.createUser                       avgt       3   4.852 ± 1.267   ms/op
ClientPb.existUser                        avgt       3   4.644 ± 0.552   ms/op
ClientPb.getUser                          avgt       3   5.015 ± 1.542   ms/op
ClientPb.listUser                         avgt       3   5.782 ± 0.735   ms/op
ClientPb.createUser                     sample  192496   4.984 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.696           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.751           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.175           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.547           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.276           ms/op
ClientPb.existUser                      sample  203414   4.719 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.147           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.357           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.765           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.307           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.554           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.608           ms/op
ClientPb.getUser                        sample  190994   5.022 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.013           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.764           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.741           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.354           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  168541   5.694 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.685           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.537           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.519           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.658           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.478           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.438           ms/op
