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
# Warmup Iteration   1: 1.583 ops/ms
# Warmup Iteration   2: 3.674 ops/ms
# Warmup Iteration   3: 6.923 ops/ms
Iteration   1: 7.554 ops/ms
Iteration   2: 7.759 ops/ms
Iteration   3: 7.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.620 ±(99.9%) 2.184 ops/ms [Average]
  (min, avg, max) = (7.548, 7.620, 7.759), stdev = 0.120
  CI (99.9%): [5.436, 9.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.371 ops/ms
# Warmup Iteration   2: 6.555 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 8.036 ops/ms
Iteration   2: 8.329 ops/ms
Iteration   3: 8.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.187 ±(99.9%) 2.675 ops/ms [Average]
  (min, avg, max) = (8.036, 8.187, 8.329), stdev = 0.147
  CI (99.9%): [5.513, 10.862] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 6.013 ops/ms
# Warmup Iteration   3: 7.490 ops/ms
Iteration   1: 7.939 ops/ms
Iteration   2: 8.013 ops/ms
Iteration   3: 7.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.932 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (7.843, 7.932, 8.013), stdev = 0.085
  CI (99.9%): [6.376, 9.488] (assumes normal distribution)


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
# Warmup Iteration   1: 2.007 ops/ms
# Warmup Iteration   2: 5.357 ops/ms
# Warmup Iteration   3: 6.464 ops/ms
Iteration   1: 6.273 ops/ms
Iteration   2: 6.330 ops/ms
Iteration   3: 6.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.345 ±(99.9%) 1.481 ops/ms [Average]
  (min, avg, max) = (6.273, 6.345, 6.433), stdev = 0.081
  CI (99.9%): [4.865, 7.826] (assumes normal distribution)


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
# Warmup Iteration   1: 15.347 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.963 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.336 ±(99.9%) 0.006 ms/op
Iteration   1: 4.051 ±(99.9%) 0.016 ms/op
Iteration   2: 4.376 ±(99.9%) 0.006 ms/op
Iteration   3: 4.333 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.254 ±(99.9%) 3.222 ms/op [Average]
  (min, avg, max) = (4.051, 4.254, 4.376), stdev = 0.177
  CI (99.9%): [1.032, 7.476] (assumes normal distribution)


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
# Warmup Iteration   1: 12.483 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.004 ms/op
Iteration   1: 4.073 ±(99.9%) 0.008 ms/op
Iteration   2: 3.952 ±(99.9%) 0.005 ms/op
Iteration   3: 4.136 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.054 ±(99.9%) 1.701 ms/op [Average]
  (min, avg, max) = (3.952, 4.054, 4.136), stdev = 0.093
  CI (99.9%): [2.352, 5.755] (assumes normal distribution)


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
# Warmup Iteration   1: 13.432 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.117 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.004 ms/op
Iteration   1: 4.182 ±(99.9%) 0.005 ms/op
Iteration   2: 3.943 ±(99.9%) 0.004 ms/op
Iteration   3: 4.023 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.049 ±(99.9%) 2.217 ms/op [Average]
  (min, avg, max) = (3.943, 4.049, 4.182), stdev = 0.122
  CI (99.9%): [1.833, 6.266] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.120 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.809 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.815 ±(99.9%) 0.010 ms/op
Iteration   1: 4.801 ±(99.9%) 0.009 ms/op
Iteration   2: 4.834 ±(99.9%) 0.008 ms/op
Iteration   3: 4.953 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.863 ±(99.9%) 1.453 ms/op [Average]
  (min, avg, max) = (4.801, 4.863, 4.953), stdev = 0.080
  CI (99.9%): [3.410, 6.316] (assumes normal distribution)


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
# Warmup Iteration   1: 13.968 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.581 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.018 ms/op
Iteration   1: 4.207 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.950 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   8.276 ms/op
                 createUser·p0.999:  22.348 ms/op
                 createUser·p0.9999: 25.558 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 4.014 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   2.007 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.765 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 27.105 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 4.149 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   8.421 ms/op
                 createUser·p0.999:  28.398 ms/op
                 createUser·p0.9999: 34.098 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232887
  mean =      4.122 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 335 
    [ 2.500,  5.000) = 217334 
    [ 5.000,  7.500) = 12353 
    [ 7.500, 10.000) = 1950 
    [10.000, 12.500) = 485 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      7.890 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     31.738 ms/op
     p(99.9990) =     35.215 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 12.686 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.244 ±(99.9%) 0.014 ms/op
Iteration   1: 3.858 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 23.597 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.994 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   8.241 ms/op
                 existUser·p0.999:  22.938 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   3: 3.883 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.873 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 30.109 ms/op
                 existUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245280
  mean =      3.911 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 310 
    [ 2.500,  5.000) = 233467 
    [ 5.000,  7.500) = 8369 
    [ 7.500, 10.000) = 2299 
    [10.000, 12.500) = 439 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     17.742 ms/op
     p(99.9900) =     28.786 ms/op
     p(99.9990) =     30.498 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 12.849 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.384 ±(99.9%) 0.017 ms/op
Iteration   1: 4.234 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  21.921 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  14.275 ms/op
                 getUser·p0.9999: 29.590 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   3: 4.121 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.105 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  25.985 ms/op
                 getUser·p0.9999: 28.613 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233213
  mean =      4.113 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 217161 
    [ 5.000,  7.500) = 12298 
    [ 7.500, 10.000) = 2507 
    [10.000, 12.500) = 732 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     21.980 ms/op
     p(99.9900) =     28.706 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 14.810 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.688 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.000 ±(99.9%) 0.021 ms/op
Iteration   1: 4.635 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.885 ms/op
                 listUser·p0.999:  25.262 ms/op
                 listUser·p0.9999: 27.758 ms/op
                 listUser·p1.00:   28.443 ms/op

Iteration   2: 4.975 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  23.809 ms/op
                 listUser·p0.9999: 30.005 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   3: 4.738 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   9.696 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 20.128 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200992
  mean =      4.778 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 165726 
    [ 5.000,  7.500) = 29401 
    [ 7.500, 10.000) = 4059 
    [10.000, 12.500) = 1045 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     22.611 ms/op
     p(99.9900) =     27.748 ms/op
     p(99.9990) =     30.277 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.620 ± 2.184  ops/ms
ClientPb.existUser                       thrpt       3   8.187 ± 2.675  ops/ms
ClientPb.getUser                         thrpt       3   7.932 ± 1.556  ops/ms
ClientPb.listUser                        thrpt       3   6.345 ± 1.481  ops/ms
ClientPb.createUser                       avgt       3   4.254 ± 3.222   ms/op
ClientPb.existUser                        avgt       3   4.054 ± 1.701   ms/op
ClientPb.getUser                          avgt       3   4.049 ± 2.217   ms/op
ClientPb.listUser                         avgt       3   4.863 ± 1.453   ms/op
ClientPb.createUser                     sample  232887   4.122 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.489           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.872           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.738           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  245280   3.911 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.708           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.938           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.742           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.786           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.605           ms/op
ClientPb.getUser                        sample  233213   4.113 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.532           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.356           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.980           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.706           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.605           ms/op
ClientPb.listUser                       sample  200992   4.778 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.333           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.152           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.611           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.748           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.573           ms/op
