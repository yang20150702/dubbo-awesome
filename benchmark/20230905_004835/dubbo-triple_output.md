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
# Warmup Iteration   1: 1.250 ops/ms
# Warmup Iteration   2: 2.934 ops/ms
# Warmup Iteration   3: 6.124 ops/ms
Iteration   1: 5.968 ops/ms
Iteration   2: 6.670 ops/ms
Iteration   3: 6.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.358 ±(99.9%) 6.524 ops/ms [Average]
  (min, avg, max) = (5.968, 6.358, 6.670), stdev = 0.358
  CI (99.9%): [≈ 0, 12.882] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.944 ops/ms
# Warmup Iteration   2: 5.570 ops/ms
# Warmup Iteration   3: 6.430 ops/ms
Iteration   1: 6.759 ops/ms
Iteration   2: 6.583 ops/ms
Iteration   3: 6.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.631 ±(99.9%) 2.054 ops/ms [Average]
  (min, avg, max) = (6.550, 6.631, 6.759), stdev = 0.113
  CI (99.9%): [4.577, 8.685] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.963 ops/ms
# Warmup Iteration   2: 5.579 ops/ms
# Warmup Iteration   3: 6.475 ops/ms
Iteration   1: 6.327 ops/ms
Iteration   2: 6.561 ops/ms
Iteration   3: 6.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.456 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (6.327, 6.456, 6.561), stdev = 0.119
  CI (99.9%): [4.292, 8.620] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.930 ops/ms
# Warmup Iteration   2: 4.731 ops/ms
# Warmup Iteration   3: 5.672 ops/ms
Iteration   1: 5.142 ops/ms
Iteration   2: 5.135 ops/ms
Iteration   3: 5.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.256 ±(99.9%) 3.694 ops/ms [Average]
  (min, avg, max) = (5.135, 5.256, 5.489), stdev = 0.203
  CI (99.9%): [1.561, 8.950] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.078 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.333 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.101 ±(99.9%) 0.011 ms/op
Iteration   1: 5.438 ±(99.9%) 0.013 ms/op
Iteration   2: 5.154 ±(99.9%) 0.010 ms/op
Iteration   3: 5.147 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.246 ±(99.9%) 3.027 ms/op [Average]
  (min, avg, max) = (5.147, 5.246, 5.438), stdev = 0.166
  CI (99.9%): [2.219, 8.273] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 18.856 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.126 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.878 ±(99.9%) 0.009 ms/op
Iteration   1: 4.610 ±(99.9%) 0.007 ms/op
Iteration   2: 4.715 ±(99.9%) 0.008 ms/op
Iteration   3: 4.454 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.593 ±(99.9%) 2.394 ms/op [Average]
  (min, avg, max) = (4.454, 4.593, 4.715), stdev = 0.131
  CI (99.9%): [2.199, 6.986] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.459 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.219 ±(99.9%) 0.008 ms/op
Iteration   1: 5.406 ±(99.9%) 0.007 ms/op
Iteration   2: 4.886 ±(99.9%) 0.009 ms/op
Iteration   3: 5.052 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.115 ±(99.9%) 4.842 ms/op [Average]
  (min, avg, max) = (4.886, 5.115, 5.406), stdev = 0.265
  CI (99.9%): [0.273, 9.957] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.818 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.313 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.758 ±(99.9%) 0.011 ms/op
Iteration   1: 5.731 ±(99.9%) 0.015 ms/op
Iteration   2: 5.839 ±(99.9%) 0.020 ms/op
Iteration   3: 5.528 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.699 ±(99.9%) 2.881 ms/op [Average]
  (min, avg, max) = (5.528, 5.699, 5.839), stdev = 0.158
  CI (99.9%): [2.818, 8.581] (assumes normal distribution)


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
# Warmup Iteration   1: 16.252 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.866 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.519 ±(99.9%) 0.025 ms/op
Iteration   1: 4.931 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   6.226 ms/op
                 createUser·p0.95:   7.291 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  21.636 ms/op
                 createUser·p0.9999: 31.606 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 4.954 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  20.477 ms/op
                 createUser·p0.9999: 28.803 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 5.059 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   4.817 ms/op
                 createUser·p0.90:   6.218 ms/op
                 createUser·p0.95:   6.930 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  29.426 ms/op
                 createUser·p0.9999: 33.524 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 192761
  mean =      4.980 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 121236 
    [ 5.000,  7.500) = 64099 
    [ 7.500, 10.000) = 5442 
    [10.000, 12.500) = 1196 
    [12.500, 15.000) = 309 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.070 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     21.799 ms/op
     p(99.9900) =     32.076 ms/op
     p(99.9990) =     34.360 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 13.257 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 5.406 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.659 ±(99.9%) 0.016 ms/op
Iteration   1: 4.968 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.868 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  21.253 ms/op
                 existUser·p0.9999: 31.694 ms/op
                 existUser·p1.00:   32.145 ms/op

Iteration   2: 4.766 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.064 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.915 ms/op
                 existUser·p0.95:   6.627 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  24.115 ms/op
                 existUser·p0.9999: 29.360 ms/op
                 existUser·p1.00:   30.540 ms/op

Iteration   3: 4.811 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.927 ms/op
                 existUser·p0.50:   4.596 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.570 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  22.348 ms/op
                 existUser·p0.9999: 37.772 ms/op
                 existUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 197946
  mean =      4.847 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 135377 
    [ 5.000,  7.500) = 56316 
    [ 7.500, 10.000) = 4631 
    [10.000, 12.500) = 1016 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     36.334 ms/op
     p(99.9990) =     38.274 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 13.980 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.153 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.022 ms/op
Iteration   1: 4.921 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   6.021 ms/op
                 getUser·p0.95:   7.078 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  19.234 ms/op
                 getUser·p0.9999: 34.406 ms/op
                 getUser·p1.00:   43.581 ms/op

Iteration   2: 4.823 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   9.437 ms/op
                 getUser·p0.999:  15.888 ms/op
                 getUser·p0.9999: 31.154 ms/op
                 getUser·p1.00:   31.392 ms/op

Iteration   3: 4.843 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   7.053 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  15.334 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 197332
  mean =      4.862 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 135383 
    [ 5.000, 10.000) = 60094 
    [10.000, 15.000) = 1613 
    [15.000, 20.000) = 50 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     16.996 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     37.904 ms/op
     p(99.9999) =     43.581 ms/op
    p(100.0000) =     43.581 ms/op


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
# Warmup Iteration   1: 17.265 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 7.137 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.603 ±(99.9%) 0.023 ms/op
Iteration   1: 5.914 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.403 ms/op
                 listUser·p0.999:  25.688 ms/op
                 listUser·p0.9999: 27.787 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   2: 6.864 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.486 ms/op
                 listUser·p0.50:   6.316 ms/op
                 listUser·p0.90:   9.241 ms/op
                 listUser·p0.95:   10.551 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  30.084 ms/op
                 listUser·p0.9999: 34.428 ms/op
                 listUser·p1.00:   35.586 ms/op

Iteration   3: 6.507 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   8.831 ms/op
                 listUser·p0.95:   10.076 ms/op
                 listUser·p0.99:   13.320 ms/op
                 listUser·p0.999:  23.588 ms/op
                 listUser·p0.9999: 35.979 ms/op
                 listUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149842
  mean =      6.404 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 21635 
    [ 5.000,  7.500) = 102637 
    [ 7.500, 10.000) = 18331 
    [10.000, 12.500) = 5058 
    [12.500, 15.000) = 1490 
    [15.000, 17.500) = 329 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      5.906 ms/op
     p(90.0000) =      8.618 ms/op
     p(95.0000) =      9.945 ms/op
     p(99.0000) =     13.271 ms/op
     p(99.9000) =     26.739 ms/op
     p(99.9900) =     33.689 ms/op
     p(99.9990) =     36.439 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.358 ± 6.524  ops/ms
ClientPb.existUser                       thrpt       3   6.631 ± 2.054  ops/ms
ClientPb.getUser                         thrpt       3   6.456 ± 2.164  ops/ms
ClientPb.listUser                        thrpt       3   5.256 ± 3.694  ops/ms
ClientPb.createUser                       avgt       3   5.246 ± 3.027   ms/op
ClientPb.existUser                        avgt       3   4.593 ± 2.394   ms/op
ClientPb.getUser                          avgt       3   5.115 ± 4.842   ms/op
ClientPb.listUser                         avgt       3   5.699 ± 2.881   ms/op
ClientPb.createUser                     sample  192761   4.980 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.652           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.267           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.070           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.994           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.799           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.076           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.603           ms/op
ClientPb.existUser                      sample  197946   4.847 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.824           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.470           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.348           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.334           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.339           ms/op
ClientPb.getUser                        sample  197332   4.862 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.924           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.021           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.880           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.996           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.210           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.581           ms/op
ClientPb.listUser                       sample  149842   6.404 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.486           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.906           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.945           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.271           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.739           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.689           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.831           ms/op
