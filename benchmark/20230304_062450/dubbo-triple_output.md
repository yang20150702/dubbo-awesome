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
# Warmup Iteration   1: 1.122 ops/ms
# Warmup Iteration   2: 2.651 ops/ms
# Warmup Iteration   3: 5.451 ops/ms
Iteration   1: 5.846 ops/ms
Iteration   2: 5.895 ops/ms
Iteration   3: 6.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.941 ±(99.9%) 2.249 ops/ms [Average]
  (min, avg, max) = (5.846, 5.941, 6.080), stdev = 0.123
  CI (99.9%): [3.691, 8.190] (assumes normal distribution)


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
# Warmup Iteration   1: 1.593 ops/ms
# Warmup Iteration   2: 5.138 ops/ms
# Warmup Iteration   3: 6.230 ops/ms
Iteration   1: 6.400 ops/ms
Iteration   2: 6.706 ops/ms
Iteration   3: 6.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.555 ±(99.9%) 2.798 ops/ms [Average]
  (min, avg, max) = (6.400, 6.555, 6.706), stdev = 0.153
  CI (99.9%): [3.757, 9.353] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.503 ops/ms
# Warmup Iteration   2: 4.764 ops/ms
# Warmup Iteration   3: 6.040 ops/ms
Iteration   1: 6.020 ops/ms
Iteration   2: 5.933 ops/ms
Iteration   3: 6.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.052 ±(99.9%) 2.527 ops/ms [Average]
  (min, avg, max) = (5.933, 6.052, 6.204), stdev = 0.139
  CI (99.9%): [3.525, 8.579] (assumes normal distribution)


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
# Warmup Iteration   1: 1.552 ops/ms
# Warmup Iteration   2: 3.947 ops/ms
# Warmup Iteration   3: 5.267 ops/ms
Iteration   1: 5.305 ops/ms
Iteration   2: 5.476 ops/ms
Iteration   3: 5.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.389 ±(99.9%) 1.566 ops/ms [Average]
  (min, avg, max) = (5.305, 5.389, 5.476), stdev = 0.086
  CI (99.9%): [3.823, 6.955] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.544 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 6.521 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.498 ±(99.9%) 0.012 ms/op
Iteration   1: 5.274 ±(99.9%) 0.010 ms/op
Iteration   2: 5.013 ±(99.9%) 0.017 ms/op
Iteration   3: 4.937 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.075 ±(99.9%) 3.230 ms/op [Average]
  (min, avg, max) = (4.937, 5.075, 5.274), stdev = 0.177
  CI (99.9%): [1.845, 8.304] (assumes normal distribution)


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
# Warmup Iteration   1: 16.404 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.919 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.993 ±(99.9%) 0.007 ms/op
Iteration   1: 4.718 ±(99.9%) 0.015 ms/op
Iteration   2: 4.766 ±(99.9%) 0.010 ms/op
Iteration   3: 4.872 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.785 ±(99.9%) 1.434 ms/op [Average]
  (min, avg, max) = (4.718, 4.785, 4.872), stdev = 0.079
  CI (99.9%): [3.351, 6.220] (assumes normal distribution)


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
# Warmup Iteration   1: 18.785 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.288 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.007 ms/op
Iteration   1: 5.204 ±(99.9%) 0.016 ms/op
Iteration   2: 4.933 ±(99.9%) 0.021 ms/op
Iteration   3: 5.131 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.089 ±(99.9%) 2.556 ms/op [Average]
  (min, avg, max) = (4.933, 5.089, 5.204), stdev = 0.140
  CI (99.9%): [2.533, 7.645] (assumes normal distribution)


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
# Warmup Iteration   1: 18.248 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 7.678 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.955 ±(99.9%) 0.010 ms/op
Iteration   1: 6.029 ±(99.9%) 0.018 ms/op
Iteration   2: 5.781 ±(99.9%) 0.017 ms/op
Iteration   3: 5.675 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.828 ±(99.9%) 3.312 ms/op [Average]
  (min, avg, max) = (5.675, 5.828, 6.029), stdev = 0.182
  CI (99.9%): [2.516, 9.140] (assumes normal distribution)


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
# Warmup Iteration   1: 17.958 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 5.996 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.460 ±(99.9%) 0.024 ms/op
Iteration   1: 5.120 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.400 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   6.316 ms/op
                 createUser·p0.95:   7.029 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  21.546 ms/op
                 createUser·p0.9999: 33.965 ms/op
                 createUser·p1.00:   35.455 ms/op

Iteration   2: 5.063 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   7.594 ms/op
                 createUser·p0.99:   10.207 ms/op
                 createUser·p0.999:  26.698 ms/op
                 createUser·p0.9999: 36.615 ms/op
                 createUser·p1.00:   37.880 ms/op

Iteration   3: 5.167 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.048 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  26.723 ms/op
                 createUser·p0.9999: 31.904 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 187351
  mean =      5.116 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 114972 
    [ 5.000,  7.500) = 64320 
    [ 7.500, 10.000) = 6244 
    [10.000, 12.500) = 1130 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.250 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     22.483 ms/op
     p(99.9900) =     35.258 ms/op
     p(99.9990) =     37.823 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 17.940 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 5.928 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.914 ±(99.9%) 0.015 ms/op
Iteration   1: 5.061 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   4.727 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  21.687 ms/op
                 existUser·p0.9999: 25.155 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   2: 5.138 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.422 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  21.103 ms/op
                 existUser·p0.9999: 24.274 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 5.009 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.064 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   5.931 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  21.677 ms/op
                 existUser·p0.9999: 26.419 ms/op
                 existUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189265
  mean =      5.069 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 124812 
    [ 5.000,  7.500) = 55902 
    [ 7.500, 10.000) = 6221 
    [10.000, 12.500) = 1462 
    [12.500, 15.000) = 443 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.645 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     21.290 ms/op
     p(99.9900) =     25.236 ms/op
     p(99.9990) =     26.654 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 17.817 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 6.388 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.305 ±(99.9%) 0.018 ms/op
Iteration   1: 5.288 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.720 ms/op
                 getUser·p0.50:   4.948 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.946 ms/op
                 getUser·p0.99:   10.371 ms/op
                 getUser·p0.999:  22.610 ms/op
                 getUser·p0.9999: 35.127 ms/op
                 getUser·p1.00:   35.193 ms/op

Iteration   2: 5.159 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.699 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.463 ms/op
                 getUser·p0.99:   10.781 ms/op
                 getUser·p0.999:  21.594 ms/op
                 getUser·p0.9999: 24.988 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 5.190 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.528 ms/op
                 getUser·p0.99:   10.478 ms/op
                 getUser·p0.999:  15.763 ms/op
                 getUser·p0.9999: 26.105 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184202
  mean =      5.212 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 106903 
    [ 5.000,  7.500) = 67272 
    [ 7.500, 10.000) = 7629 
    [10.000, 12.500) = 1615 
    [12.500, 15.000) = 328 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     35.138 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 19.057 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 7.677 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.111 ±(99.9%) 0.025 ms/op
Iteration   1: 5.922 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   5.612 ms/op
                 listUser·p0.90:   6.955 ms/op
                 listUser·p0.95:   8.126 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  23.922 ms/op
                 listUser·p0.9999: 31.438 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 6.021 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.260 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  26.143 ms/op
                 listUser·p0.9999: 29.262 ms/op
                 listUser·p1.00:   30.245 ms/op

Iteration   3: 6.075 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   7.324 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 25.934 ms/op
                 listUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159667
  mean =      6.005 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 16654 
    [ 5.000,  7.500) = 129901 
    [ 7.500, 10.000) = 9216 
    [10.000, 12.500) = 2626 
    [12.500, 15.000) = 620 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     23.866 ms/op
     p(99.9900) =     29.427 ms/op
     p(99.9990) =     33.154 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.941 ± 2.249  ops/ms
ClientPb.existUser                       thrpt       3   6.555 ± 2.798  ops/ms
ClientPb.getUser                         thrpt       3   6.052 ± 2.527  ops/ms
ClientPb.listUser                        thrpt       3   5.389 ± 1.566  ops/ms
ClientPb.createUser                       avgt       3   5.075 ± 3.230   ms/op
ClientPb.existUser                        avgt       3   4.785 ± 1.434   ms/op
ClientPb.getUser                          avgt       3   5.089 ± 2.556   ms/op
ClientPb.listUser                         avgt       3   5.828 ± 3.312   ms/op
ClientPb.createUser                     sample  187351   5.116 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.618           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.792           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.316           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.250           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.880           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.483           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.258           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.880           ms/op
ClientPb.existUser                      sample  189265   5.069 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.645           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.299           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.355           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.290           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.236           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.771           ms/op
ClientPb.getUser                        sample  184202   5.212 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.519           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.398           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.537           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  159667   6.005 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.309           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.866           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.427           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.210           ms/op
