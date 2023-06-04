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
# Warmup Iteration   1: 2.022 ops/ms
# Warmup Iteration   2: 5.325 ops/ms
# Warmup Iteration   3: 8.663 ops/ms
Iteration   1: 8.976 ops/ms
Iteration   2: 9.374 ops/ms
Iteration   3: 9.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.254 ±(99.9%) 4.399 ops/ms [Average]
  (min, avg, max) = (8.976, 9.254, 9.412), stdev = 0.241
  CI (99.9%): [4.855, 13.653] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.906 ops/ms
# Warmup Iteration   2: 8.707 ops/ms
# Warmup Iteration   3: 9.290 ops/ms
Iteration   1: 9.341 ops/ms
Iteration   2: 9.279 ops/ms
Iteration   3: 9.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.397 ±(99.9%) 2.817 ops/ms [Average]
  (min, avg, max) = (9.279, 9.397, 9.572), stdev = 0.154
  CI (99.9%): [6.580, 12.215] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.625 ops/ms
# Warmup Iteration   2: 7.767 ops/ms
# Warmup Iteration   3: 8.548 ops/ms
Iteration   1: 9.202 ops/ms
Iteration   2: 8.995 ops/ms
Iteration   3: 9.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.104 ±(99.9%) 1.895 ops/ms [Average]
  (min, avg, max) = (8.995, 9.104, 9.202), stdev = 0.104
  CI (99.9%): [7.210, 10.999] (assumes normal distribution)


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
# Warmup Iteration   1: 2.773 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 7.765 ops/ms
Iteration   1: 8.023 ops/ms
Iteration   2: 7.834 ops/ms
Iteration   3: 8.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.961 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (7.834, 7.961, 8.025), stdev = 0.109
  CI (99.9%): [5.968, 9.953] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.526 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.004 ms/op
Iteration   1: 3.394 ±(99.9%) 0.009 ms/op
Iteration   2: 3.544 ±(99.9%) 0.004 ms/op
Iteration   3: 3.361 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.433 ±(99.9%) 1.774 ms/op [Average]
  (min, avg, max) = (3.361, 3.433, 3.544), stdev = 0.097
  CI (99.9%): [1.659, 5.207] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 10.195 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.006 ms/op
Iteration   1: 3.413 ±(99.9%) 0.010 ms/op
Iteration   2: 3.475 ±(99.9%) 0.003 ms/op
Iteration   3: 3.342 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.410 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.342, 3.410, 3.475), stdev = 0.067
  CI (99.9%): [2.197, 4.623] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.839 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.008 ms/op
Iteration   1: 3.836 ±(99.9%) 0.003 ms/op
Iteration   2: 3.493 ±(99.9%) 0.009 ms/op
Iteration   3: 3.413 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.581 ±(99.9%) 4.097 ms/op [Average]
  (min, avg, max) = (3.413, 3.581, 3.836), stdev = 0.225
  CI (99.9%): [≈ 0, 7.677] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.980 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.709 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.011 ms/op
Iteration   1: 4.076 ±(99.9%) 0.010 ms/op
Iteration   2: 3.958 ±(99.9%) 0.014 ms/op
Iteration   3: 4.042 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.025 ±(99.9%) 1.115 ms/op [Average]
  (min, avg, max) = (3.958, 4.025, 4.076), stdev = 0.061
  CI (99.9%): [2.911, 5.140] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.744 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.014 ms/op
Iteration   1: 3.582 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  21.445 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.378 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  23.145 ms/op
                 createUser·p0.9999: 25.384 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.654 ms/op
                 createUser·p0.999:  20.355 ms/op
                 createUser·p0.9999: 27.230 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274418
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8732 
    [ 2.500,  5.000) = 260000 
    [ 5.000,  7.500) = 4496 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     21.023 ms/op
     p(99.9900) =     26.480 ms/op
     p(99.9990) =     29.017 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.687 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
Iteration   1: 3.393 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  21.617 ms/op
                 existUser·p0.9999: 24.789 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  23.557 ms/op
                 existUser·p0.9999: 32.537 ms/op
                 existUser·p1.00:   33.423 ms/op

Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  12.604 ms/op
                 existUser·p0.9999: 25.299 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283871
  mean =      3.379 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4918 
    [ 2.500,  5.000) = 273039 
    [ 5.000,  7.500) = 4684 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 142 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     12.632 ms/op
     p(99.9900) =     31.084 ms/op
     p(99.9990) =     33.139 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.908 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.012 ms/op
Iteration   1: 3.551 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.361 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  22.100 ms/op
                 getUser·p0.9999: 25.360 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.715 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  24.387 ms/op
                 getUser·p0.9999: 31.974 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   3: 3.584 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  19.865 ms/op
                 getUser·p0.9999: 29.559 ms/op
                 getUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265522
  mean =      3.615 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4543 
    [ 2.500,  5.000) = 251699 
    [ 5.000,  7.500) = 7688 
    [ 7.500, 10.000) = 1026 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     21.791 ms/op
     p(99.9900) =     29.848 ms/op
     p(99.9990) =     32.431 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.242 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.824 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.015 ms/op
Iteration   1: 4.237 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  23.495 ms/op
                 listUser·p0.9999: 27.714 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   2: 4.155 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 19.171 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232126
  mean =      4.134 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 222382 
    [ 5.000,  7.500) = 6756 
    [ 7.500, 10.000) = 1870 
    [10.000, 12.500) = 479 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 179 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     18.346 ms/op
     p(99.9900) =     26.240 ms/op
     p(99.9990) =     27.908 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.254 ± 4.399  ops/ms
ClientPb.existUser                       thrpt       3   9.397 ± 2.817  ops/ms
ClientPb.getUser                         thrpt       3   9.104 ± 1.895  ops/ms
ClientPb.listUser                        thrpt       3   7.961 ± 1.993  ops/ms
ClientPb.createUser                       avgt       3   3.433 ± 1.774   ms/op
ClientPb.existUser                        avgt       3   3.410 ± 1.213   ms/op
ClientPb.getUser                          avgt       3   3.581 ± 4.097   ms/op
ClientPb.listUser                         avgt       3   4.025 ± 1.115   ms/op
ClientPb.createUser                     sample  274418   3.497 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.331           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.023           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.480           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  283871   3.379 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.311           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.632           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.084           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.423           ms/op
ClientPb.getUser                        sample  265522   3.615 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.430           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.473           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.791           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.848           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.013           ms/op
ClientPb.listUser                       sample  232126   4.134 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.346           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.240           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.984           ms/op
