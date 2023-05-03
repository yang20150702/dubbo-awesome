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
# Warmup Iteration   1: 1.057 ops/ms
# Warmup Iteration   2: 2.412 ops/ms
# Warmup Iteration   3: 4.791 ops/ms
Iteration   1: 5.430 ops/ms
Iteration   2: 5.413 ops/ms
Iteration   3: 5.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.572 ±(99.9%) 4.776 ops/ms [Average]
  (min, avg, max) = (5.413, 5.572, 5.874), stdev = 0.262
  CI (99.9%): [0.796, 10.348] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.477 ops/ms
# Warmup Iteration   2: 4.399 ops/ms
# Warmup Iteration   3: 5.503 ops/ms
Iteration   1: 5.635 ops/ms
Iteration   2: 5.899 ops/ms
Iteration   3: 5.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.757 ±(99.9%) 2.427 ops/ms [Average]
  (min, avg, max) = (5.635, 5.757, 5.899), stdev = 0.133
  CI (99.9%): [3.330, 8.184] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.381 ops/ms
# Warmup Iteration   2: 4.432 ops/ms
# Warmup Iteration   3: 5.567 ops/ms
Iteration   1: 5.339 ops/ms
Iteration   2: 5.680 ops/ms
Iteration   3: 5.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.570 ±(99.9%) 3.639 ops/ms [Average]
  (min, avg, max) = (5.339, 5.570, 5.690), stdev = 0.199
  CI (99.9%): [1.931, 9.209] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.453 ops/ms
# Warmup Iteration   2: 4.085 ops/ms
# Warmup Iteration   3: 4.908 ops/ms
Iteration   1: 4.879 ops/ms
Iteration   2: 4.906 ops/ms
Iteration   3: 5.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.943 ±(99.9%) 1.603 ops/ms [Average]
  (min, avg, max) = (4.879, 4.943, 5.043), stdev = 0.088
  CI (99.9%): [3.340, 6.546] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 20.252 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.484 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.909 ±(99.9%) 0.010 ms/op
Iteration   1: 5.476 ±(99.9%) 0.020 ms/op
Iteration   2: 5.498 ±(99.9%) 0.009 ms/op
Iteration   3: 5.397 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.457 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (5.397, 5.457, 5.498), stdev = 0.053
  CI (99.9%): [4.488, 6.426] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.696 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.397 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.522 ±(99.9%) 0.005 ms/op
Iteration   1: 5.359 ±(99.9%) 0.009 ms/op
Iteration   2: 5.151 ±(99.9%) 0.018 ms/op
Iteration   3: 5.391 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.301 ±(99.9%) 2.379 ms/op [Average]
  (min, avg, max) = (5.151, 5.301, 5.391), stdev = 0.130
  CI (99.9%): [2.922, 7.679] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.410 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 7.669 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.979 ±(99.9%) 0.013 ms/op
Iteration   1: 5.720 ±(99.9%) 0.011 ms/op
Iteration   2: 5.588 ±(99.9%) 0.010 ms/op
Iteration   3: 5.489 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.599 ±(99.9%) 2.116 ms/op [Average]
  (min, avg, max) = (5.489, 5.599, 5.720), stdev = 0.116
  CI (99.9%): [3.483, 7.715] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.384 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 8.269 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.328 ±(99.9%) 0.022 ms/op
Iteration   1: 6.501 ±(99.9%) 0.012 ms/op
Iteration   2: 6.607 ±(99.9%) 0.007 ms/op
Iteration   3: 6.601 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.570 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (6.501, 6.570, 6.607), stdev = 0.059
  CI (99.9%): [5.485, 7.655] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.636 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 7.409 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.953 ±(99.9%) 0.025 ms/op
Iteration   1: 5.602 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.630 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.881 ms/op
                 createUser·p0.99:   10.453 ms/op
                 createUser·p0.999:  25.756 ms/op
                 createUser·p0.9999: 34.398 ms/op
                 createUser·p1.00:   36.897 ms/op

Iteration   2: 5.284 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.234 ms/op
                 createUser·p0.95:   6.988 ms/op
                 createUser·p0.99:   10.133 ms/op
                 createUser·p0.999:  27.828 ms/op
                 createUser·p0.9999: 30.725 ms/op
                 createUser·p1.00:   31.687 ms/op

Iteration   3: 5.688 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.062 ms/op
                 createUser·p0.95:   8.290 ms/op
                 createUser·p0.99:   11.026 ms/op
                 createUser·p0.999:  29.640 ms/op
                 createUser·p0.9999: 31.949 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173860
  mean =      5.519 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 66057 
    [ 5.000,  7.500) = 97817 
    [ 7.500, 10.000) = 7742 
    [10.000, 12.500) = 1416 
    [12.500, 15.000) = 438 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.766 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     26.612 ms/op
     p(99.9900) =     33.391 ms/op
     p(99.9990) =     36.848 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.433 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.391 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.531 ±(99.9%) 0.020 ms/op
Iteration   1: 5.478 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   8.012 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  16.073 ms/op
                 existUser·p0.9999: 27.852 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   2: 5.451 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.726 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.561 ms/op
                 existUser·p0.99:   10.650 ms/op
                 existUser·p0.999:  27.787 ms/op
                 existUser·p0.9999: 33.957 ms/op
                 existUser·p1.00:   34.079 ms/op

Iteration   3: 5.443 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.548 ms/op
                 existUser·p0.50:   5.145 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.610 ms/op
                 existUser·p0.99:   10.654 ms/op
                 existUser·p0.999:  28.936 ms/op
                 existUser·p0.9999: 35.127 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175753
  mean =      5.457 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 70710 
    [ 5.000,  7.500) = 94874 
    [ 7.500, 10.000) = 7893 
    [10.000, 12.500) = 1473 
    [12.500, 15.000) = 457 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     25.076 ms/op
     p(99.9900) =     34.500 ms/op
     p(99.9990) =     35.290 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.946 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 7.314 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.002 ±(99.9%) 0.027 ms/op
Iteration   1: 5.872 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.744 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   7.242 ms/op
                 getUser·p0.95:   8.929 ms/op
                 getUser·p0.99:   13.844 ms/op
                 getUser·p0.999:  20.021 ms/op
                 getUser·p0.9999: 30.149 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   2: 5.661 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   7.895 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  27.361 ms/op
                 getUser·p0.9999: 30.537 ms/op
                 getUser·p1.00:   32.178 ms/op

Iteration   3: 5.658 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.731 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.568 ms/op
                 getUser·p0.999:  27.656 ms/op
                 getUser·p0.9999: 32.178 ms/op
                 getUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167608
  mean =      5.728 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 43462 
    [ 5.000,  7.500) = 112148 
    [ 7.500, 10.000) = 8688 
    [10.000, 12.500) = 2038 
    [12.500, 15.000) = 687 
    [15.000, 17.500) = 280 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      8.217 ms/op
     p(99.0000) =     11.582 ms/op
     p(99.9000) =     23.282 ms/op
     p(99.9900) =     31.423 ms/op
     p(99.9990) =     32.721 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 20.267 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 8.642 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 6.919 ±(99.9%) 0.036 ms/op
Iteration   1: 6.377 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.117 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  27.849 ms/op
                 listUser·p0.9999: 31.817 ms/op
                 listUser·p1.00:   33.128 ms/op

Iteration   2: 6.327 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  30.097 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.751 ms/op

Iteration   3: 6.656 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  25.164 ms/op
                 listUser·p0.9999: 36.713 ms/op
                 listUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148650
  mean =      6.450 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 3941 
    [ 5.000,  7.500) = 127610 
    [ 7.500, 10.000) = 13451 
    [10.000, 12.500) = 2469 
    [12.500, 15.000) = 655 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      6.111 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     11.837 ms/op
     p(99.9000) =     28.541 ms/op
     p(99.9900) =     35.294 ms/op
     p(99.9990) =     36.899 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.572 ± 4.776  ops/ms
ClientPb.existUser                       thrpt       3   5.757 ± 2.427  ops/ms
ClientPb.getUser                         thrpt       3   5.570 ± 3.639  ops/ms
ClientPb.listUser                        thrpt       3   4.943 ± 1.603  ops/ms
ClientPb.createUser                       avgt       3   5.457 ± 0.969   ms/op
ClientPb.existUser                        avgt       3   5.301 ± 2.379   ms/op
ClientPb.getUser                          avgt       3   5.599 ± 2.116   ms/op
ClientPb.listUser                         avgt       3   6.570 ± 1.085   ms/op
ClientPb.createUser                     sample  173860   5.519 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.766           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.551           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.612           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.391           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.897           ms/op
ClientPb.existUser                      sample  175753   5.457 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.708           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.733           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.519           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.076           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  167608   5.728 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.556           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.217           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.582           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.282           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.423           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  148650   6.450 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.085           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.111           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.837           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.541           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.294           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.962           ms/op
