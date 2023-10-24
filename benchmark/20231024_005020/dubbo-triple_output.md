# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.518 ops/ms
# Warmup Iteration   2: 5.805 ops/ms
# Warmup Iteration   3: 9.180 ops/ms
Iteration   1: 9.663 ops/ms
Iteration   2: 9.817 ops/ms
Iteration   3: 9.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.718 ±(99.9%) 1.557 ops/ms [Average]
  (min, avg, max) = (9.663, 9.718, 9.817), stdev = 0.085
  CI (99.9%): [8.161, 11.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.152 ops/ms
# Warmup Iteration   2: 9.215 ops/ms
# Warmup Iteration   3: 10.167 ops/ms
Iteration   1: 10.057 ops/ms
Iteration   2: 10.141 ops/ms
Iteration   3: 10.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.090 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (10.057, 10.090, 10.141), stdev = 0.045
  CI (99.9%): [9.261, 10.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 9.257 ops/ms
# Warmup Iteration   3: 9.847 ops/ms
Iteration   1: 9.925 ops/ms
Iteration   2: 10.114 ops/ms
Iteration   3: 9.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.001 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (9.925, 10.001, 10.114), stdev = 0.100
  CI (99.9%): [8.184, 11.818] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.107 ops/ms
# Warmup Iteration   2: 7.702 ops/ms
# Warmup Iteration   3: 8.334 ops/ms
Iteration   1: 8.392 ops/ms
Iteration   2: 8.251 ops/ms
Iteration   3: 8.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.346 ±(99.9%) 1.504 ops/ms [Average]
  (min, avg, max) = (8.251, 8.346, 8.395), stdev = 0.082
  CI (99.9%): [6.842, 9.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.734 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.004 ms/op
Iteration   1: 3.281 ±(99.9%) 0.002 ms/op
Iteration   2: 3.252 ±(99.9%) 0.006 ms/op
Iteration   3: 3.283 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.272 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.252, 3.272, 3.283), stdev = 0.017
  CI (99.9%): [2.953, 3.591] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.828 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.004 ms/op
Iteration   1: 3.178 ±(99.9%) 0.003 ms/op
Iteration   2: 3.156 ±(99.9%) 0.005 ms/op
Iteration   3: 3.122 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.152 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.122, 3.152, 3.178), stdev = 0.028
  CI (99.9%): [2.642, 3.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.145 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.004 ms/op
Iteration   1: 3.251 ±(99.9%) 0.005 ms/op
Iteration   2: 3.251 ±(99.9%) 0.004 ms/op
Iteration   3: 3.240 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.247 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (3.240, 3.247, 3.251), stdev = 0.007
  CI (99.9%): [3.128, 3.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.788 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.341 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.004 ms/op
Iteration   1: 3.916 ±(99.9%) 0.004 ms/op
Iteration   2: 3.930 ±(99.9%) 0.003 ms/op
Iteration   3: 3.890 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.912 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.890, 3.912, 3.930), stdev = 0.020
  CI (99.9%): [3.545, 4.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.013 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  11.664 ms/op
                 createUser·p0.9999: 23.377 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  17.688 ms/op
                 createUser·p0.9999: 23.011 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  15.827 ms/op
                 createUser·p0.9999: 24.525 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290410
  mean =      3.304 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10570 
    [ 2.500,  5.000) = 275227 
    [ 5.000,  7.500) = 3684 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     23.951 ms/op
     p(99.9990) =     24.776 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.893 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.008 ms/op
Iteration   1: 3.230 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  14.990 ms/op
                 existUser·p0.9999: 17.406 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   2: 3.138 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  8.284 ms/op
                 existUser·p0.9999: 18.809 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  14.204 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301037
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10732 
    [ 2.500,  5.000) = 285837 
    [ 5.000,  7.500) = 3517 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     12.844 ms/op
     p(99.9900) =     19.782 ms/op
     p(99.9990) =     21.331 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.935 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
Iteration   1: 3.385 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  19.923 ms/op
                 getUser·p0.9999: 21.743 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  14.603 ms/op
                 getUser·p0.9999: 23.265 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.624 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  10.253 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290687
  mean =      3.302 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6415 
    [ 2.500,  5.000) = 278200 
    [ 5.000,  7.500) = 5005 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 217 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     16.994 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.022 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.730 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.011 ms/op
Iteration   1: 3.893 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.857 ms/op
                 listUser·p0.9999: 21.376 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 3.861 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.535 ms/op
                 listUser·p0.9999: 16.183 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.825 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.644 ms/op
                 listUser·p0.9999: 15.322 ms/op
                 listUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248608
  mean =      3.859 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 241801 
    [ 5.000,  7.500) = 5441 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 332 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     20.545 ms/op
     p(99.9990) =     21.840 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.718 ± 1.557  ops/ms
ClientPb.existUser                       thrpt       3  10.090 ± 0.828  ops/ms
ClientPb.getUser                         thrpt       3  10.001 ± 1.817  ops/ms
ClientPb.listUser                        thrpt       3   8.346 ± 1.504  ops/ms
ClientPb.createUser                       avgt       3   3.272 ± 0.319   ms/op
ClientPb.existUser                        avgt       3   3.152 ± 0.510   ms/op
ClientPb.getUser                          avgt       3   3.247 ± 0.119   ms/op
ClientPb.listUser                         avgt       3   3.912 ± 0.367   ms/op
ClientPb.createUser                     sample  290410   3.304 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.303           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.843           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.951           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.838           ms/op
ClientPb.existUser                      sample  301037   3.188 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.782           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.430           ms/op
ClientPb.getUser                        sample  290687   3.302 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.046           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.994           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.216           ms/op
ClientPb.listUser                       sample  248608   3.859 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.421           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.783           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.287           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.545           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.249           ms/op
