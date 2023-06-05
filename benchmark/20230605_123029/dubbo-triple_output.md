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
# Warmup Iteration   1: 0.954 ops/ms
# Warmup Iteration   2: 2.164 ops/ms
# Warmup Iteration   3: 4.498 ops/ms
Iteration   1: 4.975 ops/ms
Iteration   2: 5.003 ops/ms
Iteration   3: 5.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.088 ±(99.9%) 3.120 ops/ms [Average]
  (min, avg, max) = (4.975, 5.088, 5.284), stdev = 0.171
  CI (99.9%): [1.968, 8.207] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.494 ops/ms
# Warmup Iteration   2: 4.566 ops/ms
# Warmup Iteration   3: 5.389 ops/ms
Iteration   1: 5.731 ops/ms
Iteration   2: 5.375 ops/ms
Iteration   3: 5.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.572 ±(99.9%) 3.303 ops/ms [Average]
  (min, avg, max) = (5.375, 5.572, 5.731), stdev = 0.181
  CI (99.9%): [2.269, 8.875] (assumes normal distribution)


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
# Warmup Iteration   1: 1.427 ops/ms
# Warmup Iteration   2: 3.569 ops/ms
# Warmup Iteration   3: 5.065 ops/ms
Iteration   1: 5.371 ops/ms
Iteration   2: 5.236 ops/ms
Iteration   3: 5.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.404 ±(99.9%) 3.411 ops/ms [Average]
  (min, avg, max) = (5.236, 5.404, 5.605), stdev = 0.187
  CI (99.9%): [1.993, 8.815] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.515 ops/ms
# Warmup Iteration   2: 3.352 ops/ms
# Warmup Iteration   3: 4.385 ops/ms
Iteration   1: 4.525 ops/ms
Iteration   2: 4.539 ops/ms
Iteration   3: 4.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.516 ±(99.9%) 0.516 ops/ms [Average]
  (min, avg, max) = (4.484, 4.516, 4.539), stdev = 0.028
  CI (99.9%): [4.000, 5.032] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.712 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.886 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.341 ±(99.9%) 0.011 ms/op
Iteration   1: 6.111 ±(99.9%) 0.014 ms/op
Iteration   2: 5.904 ±(99.9%) 0.013 ms/op
Iteration   3: 6.100 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.038 ±(99.9%) 2.121 ms/op [Average]
  (min, avg, max) = (5.904, 6.038, 6.111), stdev = 0.116
  CI (99.9%): [3.917, 8.159] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.515 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.961 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.291 ±(99.9%) 0.005 ms/op
Iteration   1: 5.738 ±(99.9%) 0.011 ms/op
Iteration   2: 5.939 ±(99.9%) 0.010 ms/op
Iteration   3: 5.711 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.796 ±(99.9%) 2.271 ms/op [Average]
  (min, avg, max) = (5.711, 5.796, 5.939), stdev = 0.124
  CI (99.9%): [3.525, 8.067] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 20.887 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.863 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.206 ±(99.9%) 0.010 ms/op
Iteration   1: 6.195 ±(99.9%) 0.012 ms/op
Iteration   2: 6.172 ±(99.9%) 0.016 ms/op
Iteration   3: 6.349 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.239 ±(99.9%) 1.753 ms/op [Average]
  (min, avg, max) = (6.172, 6.239, 6.349), stdev = 0.096
  CI (99.9%): [4.486, 7.992] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 24.189 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 9.730 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 7.313 ±(99.9%) 0.012 ms/op
Iteration   1: 7.171 ±(99.9%) 0.011 ms/op
Iteration   2: 7.009 ±(99.9%) 0.012 ms/op
Iteration   3: 6.876 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.019 ±(99.9%) 2.695 ms/op [Average]
  (min, avg, max) = (6.876, 7.019, 7.171), stdev = 0.148
  CI (99.9%): [4.323, 9.714] (assumes normal distribution)


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
# Warmup Iteration   1: 21.930 ±(99.9%) 0.352 ms/op
# Warmup Iteration   2: 7.966 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.994 ±(99.9%) 0.036 ms/op
Iteration   1: 6.191 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.523 ms/op
                 createUser·p0.50:   5.898 ms/op
                 createUser·p0.90:   7.791 ms/op
                 createUser·p0.95:   8.749 ms/op
                 createUser·p0.99:   12.190 ms/op
                 createUser·p0.999:  27.558 ms/op
                 createUser·p0.9999: 33.882 ms/op
                 createUser·p1.00:   34.275 ms/op

Iteration   2: 6.140 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.540 ms/op
                 createUser·p0.50:   5.857 ms/op
                 createUser·p0.90:   7.799 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   11.338 ms/op
                 createUser·p0.999:  29.718 ms/op
                 createUser·p0.9999: 36.818 ms/op
                 createUser·p1.00:   37.356 ms/op

Iteration   3: 6.167 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.874 ms/op
                 createUser·p0.90:   7.922 ms/op
                 createUser·p0.95:   8.749 ms/op
                 createUser·p0.99:   11.305 ms/op
                 createUser·p0.999:  23.203 ms/op
                 createUser·p0.9999: 33.701 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 155626
  mean =      6.166 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 28748 
    [ 5.000,  7.500) = 106449 
    [ 7.500, 10.000) = 17138 
    [10.000, 12.500) = 2331 
    [12.500, 15.000) = 531 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =      7.840 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.497 ms/op
     p(99.9000) =     26.251 ms/op
     p(99.9900) =     35.680 ms/op
     p(99.9990) =     37.100 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 19.330 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 7.193 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.161 ±(99.9%) 0.028 ms/op
Iteration   1: 6.000 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.544 ms/op
                 existUser·p0.50:   5.833 ms/op
                 existUser·p0.90:   7.594 ms/op
                 existUser·p0.95:   8.569 ms/op
                 existUser·p0.99:   11.403 ms/op
                 existUser·p0.999:  25.572 ms/op
                 existUser·p0.9999: 28.369 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   2: 5.894 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.351 ms/op
                 existUser·p0.50:   5.644 ms/op
                 existUser·p0.90:   7.512 ms/op
                 existUser·p0.95:   8.282 ms/op
                 existUser·p0.99:   11.527 ms/op
                 existUser·p0.999:  17.949 ms/op
                 existUser·p0.9999: 30.714 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   3: 6.014 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   2.310 ms/op
                 existUser·p0.50:   5.661 ms/op
                 existUser·p0.90:   7.660 ms/op
                 existUser·p0.95:   8.946 ms/op
                 existUser·p0.99:   12.485 ms/op
                 existUser·p0.999:  29.813 ms/op
                 existUser·p0.9999: 36.593 ms/op
                 existUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 160735
  mean =      5.969 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 44345 
    [ 5.000, 10.000) = 112739 
    [10.000, 15.000) = 3143 
    [15.000, 20.000) = 331 
    [20.000, 25.000) = 19 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      5.710 ms/op
     p(90.0000) =      7.586 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.971 ms/op
     p(99.9000) =     22.460 ms/op
     p(99.9900) =     34.982 ms/op
     p(99.9990) =     38.623 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


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
# Warmup Iteration   1: 20.177 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 7.775 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.242 ±(99.9%) 0.029 ms/op
Iteration   1: 5.931 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   5.546 ms/op
                 getUser·p0.90:   7.668 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   11.108 ms/op
                 getUser·p0.999:  31.463 ms/op
                 getUser·p0.9999: 36.045 ms/op
                 getUser·p1.00:   38.207 ms/op

Iteration   2: 5.993 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.675 ms/op
                 getUser·p0.50:   5.554 ms/op
                 getUser·p0.90:   7.602 ms/op
                 getUser·p0.95:   8.733 ms/op
                 getUser·p0.99:   13.353 ms/op
                 getUser·p0.999:  30.495 ms/op
                 getUser·p0.9999: 36.416 ms/op
                 getUser·p1.00:   37.224 ms/op

Iteration   3: 6.234 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   3.060 ms/op
                 getUser·p0.50:   5.980 ms/op
                 getUser·p0.90:   7.856 ms/op
                 getUser·p0.95:   8.880 ms/op
                 getUser·p0.99:   12.222 ms/op
                 getUser·p0.999:  16.865 ms/op
                 getUser·p0.9999: 32.067 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 158616
  mean =      6.050 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 36117 
    [ 5.000,  7.500) = 103830 
    [ 7.500, 10.000) = 14486 
    [10.000, 12.500) = 2862 
    [12.500, 15.000) = 732 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 72 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      2.343 ms/op
     p(50.0000) =      5.661 ms/op
     p(90.0000) =      7.733 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     12.108 ms/op
     p(99.9000) =     29.032 ms/op
     p(99.9900) =     35.932 ms/op
     p(99.9990) =     37.631 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 23.209 ±(99.9%) 0.417 ms/op
# Warmup Iteration   2: 10.503 ±(99.9%) 0.090 ms/op
# Warmup Iteration   3: 7.373 ±(99.9%) 0.037 ms/op
Iteration   1: 7.309 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   6.906 ms/op
                 listUser·p0.90:   9.208 ms/op
                 listUser·p0.95:   10.355 ms/op
                 listUser·p0.99:   14.310 ms/op
                 listUser·p0.999:  30.654 ms/op
                 listUser·p0.9999: 36.307 ms/op
                 listUser·p1.00:   39.584 ms/op

Iteration   2: 7.118 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.346 ms/op
                 listUser·p0.50:   6.676 ms/op
                 listUser·p0.90:   9.011 ms/op
                 listUser·p0.95:   10.437 ms/op
                 listUser·p0.99:   14.369 ms/op
                 listUser·p0.999:  32.218 ms/op
                 listUser·p0.9999: 39.945 ms/op
                 listUser·p1.00:   40.567 ms/op

Iteration   3: 6.916 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.986 ms/op
                 listUser·p0.50:   6.463 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   10.076 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  31.523 ms/op
                 listUser·p0.9999: 36.307 ms/op
                 listUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 135023
  mean =      7.111 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2769 
    [ 5.000, 10.000) = 124419 
    [10.000, 15.000) = 6909 
    [15.000, 20.000) = 575 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 101 
    [30.000, 35.000) = 143 
    [35.000, 40.000) = 41 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.404 ms/op
     p(50.0000) =      6.676 ms/op
     p(90.0000) =      9.028 ms/op
     p(95.0000) =     10.273 ms/op
     p(99.0000) =     13.894 ms/op
     p(99.9000) =     31.555 ms/op
     p(99.9900) =     38.732 ms/op
     p(99.9990) =     40.498 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.088 ± 3.120  ops/ms
ClientPb.existUser                       thrpt       3   5.572 ± 3.303  ops/ms
ClientPb.getUser                         thrpt       3   5.404 ± 3.411  ops/ms
ClientPb.listUser                        thrpt       3   4.516 ± 0.516  ops/ms
ClientPb.createUser                       avgt       3   6.038 ± 2.121   ms/op
ClientPb.existUser                        avgt       3   5.796 ± 2.271   ms/op
ClientPb.getUser                          avgt       3   6.239 ± 1.753   ms/op
ClientPb.listUser                         avgt       3   7.019 ± 2.695   ms/op
ClientPb.createUser                     sample  155626   6.166 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.380           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.840           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.716           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.251           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.680           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  160735   5.969 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.310           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.586           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.569           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.971           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.460           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.982           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.091           ms/op
ClientPb.getUser                        sample  158616   6.050 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.343           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.661           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.733           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.765           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.108           ms/op
ClientPb.getUser:getUser·p0.999         sample          29.032           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.932           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.207           ms/op
ClientPb.listUser                       sample  135023   7.111 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.404           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.028           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.273           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.894           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.555           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.732           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.567           ms/op
