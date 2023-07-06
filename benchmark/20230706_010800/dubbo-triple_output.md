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
# Warmup Iteration   1: 2.594 ops/ms
# Warmup Iteration   2: 6.252 ops/ms
# Warmup Iteration   3: 9.211 ops/ms
Iteration   1: 9.858 ops/ms
Iteration   2: 9.967 ops/ms
Iteration   3: 9.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.851 ±(99.9%) 2.172 ops/ms [Average]
  (min, avg, max) = (9.729, 9.851, 9.967), stdev = 0.119
  CI (99.9%): [7.679, 12.023] (assumes normal distribution)


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
# Warmup Iteration   1: 3.461 ops/ms
# Warmup Iteration   2: 8.811 ops/ms
# Warmup Iteration   3: 9.736 ops/ms
Iteration   1: 10.483 ops/ms
Iteration   2: 10.056 ops/ms
Iteration   3: 10.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.219 ±(99.9%) 4.211 ops/ms [Average]
  (min, avg, max) = (10.056, 10.219, 10.483), stdev = 0.231
  CI (99.9%): [6.008, 14.430] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.262 ops/ms
# Warmup Iteration   2: 8.504 ops/ms
# Warmup Iteration   3: 9.380 ops/ms
Iteration   1: 9.743 ops/ms
Iteration   2: 10.219 ops/ms
Iteration   3: 10.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.010 ±(99.9%) 4.436 ops/ms [Average]
  (min, avg, max) = (9.743, 10.010, 10.219), stdev = 0.243
  CI (99.9%): [5.573, 14.446] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.353 ops/ms
# Warmup Iteration   2: 7.627 ops/ms
# Warmup Iteration   3: 8.207 ops/ms
Iteration   1: 8.625 ops/ms
Iteration   2: 8.678 ops/ms
Iteration   3: 8.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.646 ±(99.9%) 0.519 ops/ms [Average]
  (min, avg, max) = (8.625, 8.646, 8.678), stdev = 0.028
  CI (99.9%): [8.127, 9.164] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.903 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.004 ms/op
Iteration   1: 3.212 ±(99.9%) 0.002 ms/op
Iteration   2: 3.156 ±(99.9%) 0.009 ms/op
Iteration   3: 3.221 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.196 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (3.156, 3.196, 3.221), stdev = 0.035
  CI (99.9%): [2.558, 3.834] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.197 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.005 ms/op
Iteration   1: 3.082 ±(99.9%) 0.003 ms/op
Iteration   2: 3.052 ±(99.9%) 0.008 ms/op
Iteration   3: 3.219 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.117 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (3.052, 3.117, 3.219), stdev = 0.089
  CI (99.9%): [1.495, 4.740] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.360 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.004 ms/op
Iteration   1: 3.316 ±(99.9%) 0.003 ms/op
Iteration   2: 3.203 ±(99.9%) 0.005 ms/op
Iteration   3: 3.199 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.199, 3.239, 3.316), stdev = 0.066
  CI (99.9%): [2.026, 4.452] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.841 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.006 ms/op
Iteration   1: 3.614 ±(99.9%) 0.011 ms/op
Iteration   2: 3.824 ±(99.9%) 0.004 ms/op
Iteration   3: 3.699 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.712 ±(99.9%) 1.927 ms/op [Average]
  (min, avg, max) = (3.614, 3.712, 3.824), stdev = 0.106
  CI (99.9%): [1.785, 5.640] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.035 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.010 ms/op
Iteration   1: 3.132 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  18.907 ms/op
                 createUser·p0.9999: 28.852 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 3.342 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  19.190 ms/op
                 createUser·p0.9999: 24.066 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  15.237 ms/op
                 createUser·p0.9999: 22.558 ms/op
                 createUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299759
  mean =      3.201 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15156 
    [ 2.500,  5.000) = 278958 
    [ 5.000,  7.500) = 4923 
    [ 7.500, 10.000) = 329 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     15.978 ms/op
     p(99.9900) =     27.264 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 6.463 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
Iteration   1: 3.127 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.274 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.535 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 23.101 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   2: 3.128 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  11.561 ms/op
                 existUser·p0.9999: 21.842 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 21.419 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305407
  mean =      3.142 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12979 
    [ 2.500,  5.000) = 285441 
    [ 5.000,  7.500) = 5897 
    [ 7.500, 10.000) = 749 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.274 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     11.036 ms/op
     p(99.9900) =     22.357 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 8.409 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
Iteration   1: 3.196 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  17.168 ms/op
                 getUser·p0.9999: 19.628 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  15.756 ms/op
                 getUser·p0.9999: 22.196 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.204 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.604 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  14.050 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296282
  mean =      3.240 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12443 
    [ 2.500,  5.000) = 277414 
    [ 5.000,  7.500) = 5414 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     23.531 ms/op
     p(99.9990) =     25.568 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 9.011 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.011 ms/op
Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  14.925 ms/op
                 listUser·p0.9999: 22.603 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  12.875 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 3.723 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 16.227 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253144
  mean =      3.790 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 245031 
    [ 5.000,  7.500) = 5792 
    [ 7.500, 10.000) = 1396 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 375 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     23.117 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.851 ± 2.172  ops/ms
ClientPb.existUser                       thrpt       3  10.219 ± 4.211  ops/ms
ClientPb.getUser                         thrpt       3  10.010 ± 4.436  ops/ms
ClientPb.listUser                        thrpt       3   8.646 ± 0.519  ops/ms
ClientPb.createUser                       avgt       3   3.196 ± 0.638   ms/op
ClientPb.existUser                        avgt       3   3.117 ± 1.623   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 1.213   ms/op
ClientPb.listUser                         avgt       3   3.712 ± 1.927   ms/op
ClientPb.createUser                     sample  299759   3.201 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.286           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.264           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.262           ms/op
ClientPb.existUser                      sample  305407   3.142 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.274           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.087           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.036           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.357           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.314           ms/op
ClientPb.getUser                        sample  296282   3.240 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.890           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.531           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.985           ms/op
ClientPb.listUser                       sample  253144   3.790 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.188           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.041           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.463           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.495           ms/op
