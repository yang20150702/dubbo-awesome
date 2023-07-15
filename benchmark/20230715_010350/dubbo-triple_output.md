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
# Warmup Iteration   1: 1.699 ops/ms
# Warmup Iteration   2: 3.477 ops/ms
# Warmup Iteration   3: 7.132 ops/ms
Iteration   1: 7.436 ops/ms
Iteration   2: 8.005 ops/ms
Iteration   3: 7.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.723 ±(99.9%) 5.195 ops/ms [Average]
  (min, avg, max) = (7.436, 7.723, 8.005), stdev = 0.285
  CI (99.9%): [2.528, 12.918] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.092 ops/ms
# Warmup Iteration   2: 6.924 ops/ms
# Warmup Iteration   3: 7.989 ops/ms
Iteration   1: 8.350 ops/ms
Iteration   2: 8.550 ops/ms
Iteration   3: 8.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.581 ±(99.9%) 4.515 ops/ms [Average]
  (min, avg, max) = (8.350, 8.581, 8.842), stdev = 0.247
  CI (99.9%): [4.065, 13.096] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.237 ops/ms
# Warmup Iteration   2: 6.410 ops/ms
# Warmup Iteration   3: 7.317 ops/ms
Iteration   1: 7.800 ops/ms
Iteration   2: 8.022 ops/ms
Iteration   3: 8.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.983 ±(99.9%) 3.052 ops/ms [Average]
  (min, avg, max) = (7.800, 7.983, 8.128), stdev = 0.167
  CI (99.9%): [4.931, 11.036] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.929 ops/ms
# Warmup Iteration   2: 5.548 ops/ms
# Warmup Iteration   3: 6.765 ops/ms
Iteration   1: 6.815 ops/ms
Iteration   2: 6.790 ops/ms
Iteration   3: 6.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.771 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (6.707, 6.771, 6.815), stdev = 0.057
  CI (99.9%): [5.739, 7.803] (assumes normal distribution)


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
# Warmup Iteration   1: 13.529 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.006 ms/op
Iteration   1: 3.984 ±(99.9%) 0.013 ms/op
Iteration   2: 3.983 ±(99.9%) 0.010 ms/op
Iteration   3: 4.035 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.001 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (3.983, 4.001, 4.035), stdev = 0.030
  CI (99.9%): [3.457, 4.545] (assumes normal distribution)


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
# Warmup Iteration   1: 12.590 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.003 ms/op
Iteration   1: 3.788 ±(99.9%) 0.006 ms/op
Iteration   2: 3.877 ±(99.9%) 0.008 ms/op
Iteration   3: 3.895 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.853 ±(99.9%) 1.046 ms/op [Average]
  (min, avg, max) = (3.788, 3.853, 3.895), stdev = 0.057
  CI (99.9%): [2.807, 4.899] (assumes normal distribution)


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
# Warmup Iteration   1: 11.664 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.003 ms/op
Iteration   1: 4.091 ±(99.9%) 0.006 ms/op
Iteration   2: 3.944 ±(99.9%) 0.006 ms/op
Iteration   3: 3.857 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.964 ±(99.9%) 2.152 ms/op [Average]
  (min, avg, max) = (3.857, 3.964, 4.091), stdev = 0.118
  CI (99.9%): [1.812, 6.116] (assumes normal distribution)


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
# Warmup Iteration   1: 13.865 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.319 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.806 ±(99.9%) 0.010 ms/op
Iteration   1: 4.682 ±(99.9%) 0.010 ms/op
Iteration   2: 4.538 ±(99.9%) 0.015 ms/op
Iteration   3: 4.739 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.653 ±(99.9%) 1.887 ms/op [Average]
  (min, avg, max) = (4.538, 4.653, 4.739), stdev = 0.103
  CI (99.9%): [2.766, 6.540] (assumes normal distribution)


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
# Warmup Iteration   1: 13.585 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.094 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.605 ±(99.9%) 0.021 ms/op
Iteration   1: 4.137 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   6.210 ms/op
                 createUser·p0.99:   8.266 ms/op
                 createUser·p0.999:  23.190 ms/op
                 createUser·p0.9999: 26.149 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 3.987 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.818 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  10.895 ms/op
                 createUser·p0.9999: 28.211 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 3.884 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.292 ms/op
                 createUser·p0.999:  27.008 ms/op
                 createUser·p0.9999: 31.392 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239797
  mean =      4.000 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 224837 
    [ 5.000,  7.500) = 12936 
    [ 7.500, 10.000) = 1397 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     23.141 ms/op
     p(99.9900) =     30.640 ms/op
     p(99.9990) =     31.726 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 13.305 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.012 ms/op
Iteration   1: 3.892 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  22.872 ms/op
                 existUser·p0.9999: 25.032 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 30.469 ms/op
                 existUser·p1.00:   31.228 ms/op

Iteration   3: 3.902 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.036 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   7.420 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 35.258 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245826
  mean =      3.902 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180 
    [ 2.500,  5.000) = 236936 
    [ 5.000,  7.500) = 6840 
    [ 7.500, 10.000) = 1108 
    [10.000, 12.500) = 453 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     14.561 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     35.687 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 10.957 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.013 ms/op
Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  23.772 ms/op
                 getUser·p0.9999: 28.018 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 4.158 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  17.007 ms/op
                 getUser·p0.9999: 28.430 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 3.896 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  27.689 ms/op
                 getUser·p0.9999: 31.208 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238586
  mean =      4.022 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 226628 
    [ 5.000,  7.500) = 9927 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     23.817 ms/op
     p(99.9900) =     30.114 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 14.834 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.429 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.017 ms/op
Iteration   1: 4.640 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  25.005 ms/op
                 listUser·p0.9999: 27.041 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 4.613 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  16.679 ms/op
                 listUser·p0.9999: 22.299 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 4.697 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  16.302 ms/op
                 listUser·p0.9999: 18.586 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206290
  mean =      4.650 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 178997 
    [ 5.000,  7.500) = 23584 
    [ 7.500, 10.000) = 2723 
    [10.000, 12.500) = 438 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     26.521 ms/op
     p(99.9990) =     27.386 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.723 ± 5.195  ops/ms
ClientPb.existUser                       thrpt       3   8.581 ± 4.515  ops/ms
ClientPb.getUser                         thrpt       3   7.983 ± 3.052  ops/ms
ClientPb.listUser                        thrpt       3   6.771 ± 1.032  ops/ms
ClientPb.createUser                       avgt       3   4.001 ± 0.544   ms/op
ClientPb.existUser                        avgt       3   3.853 ± 1.046   ms/op
ClientPb.getUser                          avgt       3   3.964 ± 2.152   ms/op
ClientPb.listUser                         avgt       3   4.653 ± 1.887   ms/op
ClientPb.createUser                     sample  239797   4.000 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.470           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.141           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.640           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.850           ms/op
ClientPb.existUser                      sample  245826   3.902 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.647           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.547           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.102           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.561           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.406           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.717           ms/op
ClientPb.getUser                        sample  238586   4.022 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.397           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.817           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.114           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.899           ms/op
ClientPb.listUser                       sample  206290   4.650 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.360           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.521           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
