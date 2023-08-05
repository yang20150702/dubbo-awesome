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
# Warmup Iteration   1: 0.949 ops/ms
# Warmup Iteration   2: 2.145 ops/ms
# Warmup Iteration   3: 4.605 ops/ms
Iteration   1: 5.309 ops/ms
Iteration   2: 5.340 ops/ms
Iteration   3: 5.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.465 ±(99.9%) 4.466 ops/ms [Average]
  (min, avg, max) = (5.309, 5.465, 5.747), stdev = 0.245
  CI (99.9%): [0.999, 9.931] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.390 ops/ms
# Warmup Iteration   2: 4.656 ops/ms
# Warmup Iteration   3: 5.776 ops/ms
Iteration   1: 5.739 ops/ms
Iteration   2: 5.952 ops/ms
Iteration   3: 5.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.874 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (5.739, 5.874, 5.952), stdev = 0.118
  CI (99.9%): [3.730, 8.018] (assumes normal distribution)


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
# Warmup Iteration   1: 1.379 ops/ms
# Warmup Iteration   2: 4.005 ops/ms
# Warmup Iteration   3: 5.321 ops/ms
Iteration   1: 5.458 ops/ms
Iteration   2: 5.559 ops/ms
Iteration   3: 5.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.494 ±(99.9%) 1.030 ops/ms [Average]
  (min, avg, max) = (5.458, 5.494, 5.559), stdev = 0.056
  CI (99.9%): [4.464, 6.525] (assumes normal distribution)


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
# Warmup Iteration   1: 1.400 ops/ms
# Warmup Iteration   2: 3.833 ops/ms
# Warmup Iteration   3: 4.675 ops/ms
Iteration   1: 4.554 ops/ms
Iteration   2: 4.772 ops/ms
Iteration   3: 4.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.737 ±(99.9%) 3.062 ops/ms [Average]
  (min, avg, max) = (4.554, 4.737, 4.885), stdev = 0.168
  CI (99.9%): [1.675, 7.799] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.860 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 7.571 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.234 ±(99.9%) 0.016 ms/op
Iteration   1: 5.978 ±(99.9%) 0.010 ms/op
Iteration   2: 5.748 ±(99.9%) 0.009 ms/op
Iteration   3: 5.736 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.821 ±(99.9%) 2.490 ms/op [Average]
  (min, avg, max) = (5.736, 5.821, 5.978), stdev = 0.136
  CI (99.9%): [3.331, 8.311] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 19.727 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 7.113 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.775 ±(99.9%) 0.007 ms/op
Iteration   1: 6.030 ±(99.9%) 0.008 ms/op
Iteration   2: 5.623 ±(99.9%) 0.012 ms/op
Iteration   3: 5.440 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.698 ±(99.9%) 5.508 ms/op [Average]
  (min, avg, max) = (5.440, 5.698, 6.030), stdev = 0.302
  CI (99.9%): [0.189, 11.206] (assumes normal distribution)


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
# Warmup Iteration   1: 20.561 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.595 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.745 ±(99.9%) 0.009 ms/op
Iteration   1: 5.733 ±(99.9%) 0.010 ms/op
Iteration   2: 5.815 ±(99.9%) 0.009 ms/op
Iteration   3: 5.553 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.700 ±(99.9%) 2.445 ms/op [Average]
  (min, avg, max) = (5.553, 5.700, 5.815), stdev = 0.134
  CI (99.9%): [3.255, 8.145] (assumes normal distribution)


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
# Warmup Iteration   1: 21.640 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.672 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.880 ±(99.9%) 0.014 ms/op
Iteration   1: 6.797 ±(99.9%) 0.017 ms/op
Iteration   2: 6.661 ±(99.9%) 0.013 ms/op
Iteration   3: 6.911 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.790 ±(99.9%) 2.279 ms/op [Average]
  (min, avg, max) = (6.661, 6.790, 6.911), stdev = 0.125
  CI (99.9%): [4.511, 9.068] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 21.554 ±(99.9%) 0.415 ms/op
# Warmup Iteration   2: 7.772 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.058 ±(99.9%) 0.030 ms/op
Iteration   1: 5.837 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.474 ms/op
                 createUser·p0.50:   5.505 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.652 ms/op
                 createUser·p0.99:   11.305 ms/op
                 createUser·p0.999:  22.024 ms/op
                 createUser·p0.9999: 25.253 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   2: 5.543 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.429 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.889 ms/op
                 createUser·p0.95:   7.995 ms/op
                 createUser·p0.99:   11.469 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 25.239 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 5.650 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   7.143 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.853 ms/op
                 createUser·p0.999:  25.396 ms/op
                 createUser·p0.9999: 29.327 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169215
  mean =      5.674 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 62030 
    [ 5.000,  7.500) = 93570 
    [ 7.500, 10.000) = 10130 
    [10.000, 12.500) = 2367 
    [12.500, 15.000) = 673 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     30.066 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 18.972 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 6.545 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.988 ±(99.9%) 0.025 ms/op
Iteration   1: 5.763 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.298 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.291 ms/op
                 existUser·p0.95:   8.520 ms/op
                 existUser·p0.99:   11.403 ms/op
                 existUser·p0.999:  19.825 ms/op
                 existUser·p0.9999: 26.457 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   2: 5.647 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   7.184 ms/op
                 existUser·p0.95:   8.618 ms/op
                 existUser·p0.99:   11.846 ms/op
                 existUser·p0.999:  26.575 ms/op
                 existUser·p0.9999: 31.108 ms/op
                 existUser·p1.00:   34.734 ms/op

Iteration   3: 5.733 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.580 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   7.356 ms/op
                 existUser·p0.95:   8.552 ms/op
                 existUser·p0.99:   12.009 ms/op
                 existUser·p0.999:  19.108 ms/op
                 existUser·p0.9999: 32.233 ms/op
                 existUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 167977
  mean =      5.714 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 57392 
    [ 5.000,  7.500) = 95594 
    [ 7.500, 10.000) = 11318 
    [10.000, 12.500) = 2392 
    [12.500, 15.000) = 755 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     20.613 ms/op
     p(99.9900) =     30.868 ms/op
     p(99.9990) =     34.467 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 21.168 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 7.016 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.933 ±(99.9%) 0.026 ms/op
Iteration   1: 6.083 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.798 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   8.118 ms/op
                 getUser·p0.95:   9.650 ms/op
                 getUser·p0.99:   14.205 ms/op
                 getUser·p0.999:  25.978 ms/op
                 getUser·p0.9999: 29.057 ms/op
                 getUser·p1.00:   30.278 ms/op

Iteration   2: 5.987 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.769 ms/op
                 getUser·p0.50:   5.628 ms/op
                 getUser·p0.90:   7.373 ms/op
                 getUser·p0.95:   8.471 ms/op
                 getUser·p0.99:   12.435 ms/op
                 getUser·p0.999:  26.267 ms/op
                 getUser·p0.9999: 32.155 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   3: 5.789 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.871 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.053 ms/op
                 getUser·p0.95:   8.028 ms/op
                 getUser·p0.99:   11.649 ms/op
                 getUser·p0.999:  17.095 ms/op
                 getUser·p0.9999: 33.520 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 161302
  mean =      5.950 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 33488 
    [ 5.000,  7.500) = 112340 
    [ 7.500, 10.000) = 10751 
    [10.000, 12.500) = 2849 
    [12.500, 15.000) = 1063 
    [15.000, 17.500) = 464 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.769 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      7.438 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.927 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     32.722 ms/op
     p(99.9990) =     34.271 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 23.596 ±(99.9%) 0.391 ms/op
# Warmup Iteration   2: 8.205 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.896 ±(99.9%) 0.030 ms/op
Iteration   1: 6.742 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   9.961 ms/op
                 listUser·p0.99:   13.566 ms/op
                 listUser·p0.999:  27.671 ms/op
                 listUser·p0.9999: 32.757 ms/op
                 listUser·p1.00:   33.817 ms/op

Iteration   2: 6.511 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   8.135 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   13.304 ms/op
                 listUser·p0.999:  32.080 ms/op
                 listUser·p0.9999: 34.412 ms/op
                 listUser·p1.00:   34.800 ms/op

Iteration   3: 6.586 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.015 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.233 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   13.385 ms/op
                 listUser·p0.999:  25.539 ms/op
                 listUser·p0.9999: 29.741 ms/op
                 listUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145193
  mean =      6.612 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 4936 
    [ 5.000,  7.500) = 117328 
    [ 7.500, 10.000) = 16515 
    [10.000, 12.500) = 4271 
    [12.500, 15.000) = 1298 
    [15.000, 17.500) = 396 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 65 
    [32.500, 35.000) = 49 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      6.152 ms/op
     p(90.0000) =      8.298 ms/op
     p(95.0000) =      9.765 ms/op
     p(99.0000) =     13.402 ms/op
     p(99.9000) =     29.327 ms/op
     p(99.9900) =     34.241 ms/op
     p(99.9990) =     34.740 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.465 ± 4.466  ops/ms
ClientPb.existUser                       thrpt       3   5.874 ± 2.144  ops/ms
ClientPb.getUser                         thrpt       3   5.494 ± 1.030  ops/ms
ClientPb.listUser                        thrpt       3   4.737 ± 3.062  ops/ms
ClientPb.createUser                       avgt       3   5.821 ± 2.490   ms/op
ClientPb.existUser                        avgt       3   5.698 ± 5.508   ms/op
ClientPb.getUser                          avgt       3   5.700 ± 2.445   ms/op
ClientPb.listUser                         avgt       3   6.790 ± 2.279   ms/op
ClientPb.createUser                     sample  169215   5.674 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.691           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.143           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.421           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.633           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.513           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.787           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.769           ms/op
ClientPb.existUser                      sample  167977   5.714 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.081           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.291           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.569           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.731           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.613           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.868           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.734           ms/op
ClientPb.getUser                        sample  161302   5.950 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.769           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.438           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.831           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.927           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.362           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.722           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  145193   6.612 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.889           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.152           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.298           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.402           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.327           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.241           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.800           ms/op
