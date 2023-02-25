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
# Warmup Iteration   1: 0.972 ops/ms
# Warmup Iteration   2: 2.209 ops/ms
# Warmup Iteration   3: 5.200 ops/ms
Iteration   1: 5.488 ops/ms
Iteration   2: 5.774 ops/ms
Iteration   3: 5.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.608 ±(99.9%) 2.701 ops/ms [Average]
  (min, avg, max) = (5.488, 5.608, 5.774), stdev = 0.148
  CI (99.9%): [2.908, 8.309] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.575 ops/ms
# Warmup Iteration   2: 4.931 ops/ms
# Warmup Iteration   3: 5.854 ops/ms
Iteration   1: 5.869 ops/ms
Iteration   2: 5.597 ops/ms
Iteration   3: 5.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.721 ±(99.9%) 2.509 ops/ms [Average]
  (min, avg, max) = (5.597, 5.721, 5.869), stdev = 0.138
  CI (99.9%): [3.212, 8.230] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.520 ops/ms
# Warmup Iteration   2: 4.661 ops/ms
# Warmup Iteration   3: 5.526 ops/ms
Iteration   1: 5.768 ops/ms
Iteration   2: 5.969 ops/ms
Iteration   3: 5.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.765 ±(99.9%) 3.766 ops/ms [Average]
  (min, avg, max) = (5.557, 5.765, 5.969), stdev = 0.206
  CI (99.9%): [1.999, 9.530] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.405 ops/ms
# Warmup Iteration   2: 4.086 ops/ms
# Warmup Iteration   3: 4.740 ops/ms
Iteration   1: 4.848 ops/ms
Iteration   2: 4.948 ops/ms
Iteration   3: 4.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.864 ±(99.9%) 1.406 ops/ms [Average]
  (min, avg, max) = (4.797, 4.864, 4.948), stdev = 0.077
  CI (99.9%): [3.458, 6.270] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.885 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.239 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.442 ±(99.9%) 0.013 ms/op
Iteration   1: 5.851 ±(99.9%) 0.015 ms/op
Iteration   2: 5.647 ±(99.9%) 0.028 ms/op
Iteration   3: 5.939 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.812 ±(99.9%) 2.737 ms/op [Average]
  (min, avg, max) = (5.647, 5.812, 5.939), stdev = 0.150
  CI (99.9%): [3.075, 8.549] (assumes normal distribution)


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
# Warmup Iteration   1: 18.019 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.278 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.540 ±(99.9%) 0.008 ms/op
Iteration   1: 5.325 ±(99.9%) 0.012 ms/op
Iteration   2: 5.492 ±(99.9%) 0.009 ms/op
Iteration   3: 5.436 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.418 ±(99.9%) 1.544 ms/op [Average]
  (min, avg, max) = (5.325, 5.418, 5.492), stdev = 0.085
  CI (99.9%): [3.873, 6.962] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 18.634 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.151 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.440 ±(99.9%) 0.011 ms/op
Iteration   1: 5.426 ±(99.9%) 0.010 ms/op
Iteration   2: 5.650 ±(99.9%) 0.009 ms/op
Iteration   3: 5.969 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.682 ±(99.9%) 4.980 ms/op [Average]
  (min, avg, max) = (5.426, 5.682, 5.969), stdev = 0.273
  CI (99.9%): [0.702, 10.662] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 22.360 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 8.886 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.616 ±(99.9%) 0.011 ms/op
Iteration   1: 6.122 ±(99.9%) 0.014 ms/op
Iteration   2: 6.199 ±(99.9%) 0.017 ms/op
Iteration   3: 6.254 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.192 ±(99.9%) 1.208 ms/op [Average]
  (min, avg, max) = (6.122, 6.192, 6.254), stdev = 0.066
  CI (99.9%): [4.984, 7.400] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.843 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.918 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.558 ±(99.9%) 0.022 ms/op
Iteration   1: 5.511 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   7.160 ms/op
                 createUser·p0.95:   8.097 ms/op
                 createUser·p0.99:   10.764 ms/op
                 createUser·p0.999:  25.068 ms/op
                 createUser·p0.9999: 30.618 ms/op
                 createUser·p1.00:   31.687 ms/op

Iteration   2: 5.471 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.060 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.898 ms/op
                 createUser·p0.95:   7.873 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  27.789 ms/op
                 createUser·p0.9999: 32.609 ms/op
                 createUser·p1.00:   33.751 ms/op

Iteration   3: 5.184 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.545 ms/op
                 createUser·p0.95:   7.381 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  14.347 ms/op
                 createUser·p0.9999: 30.326 ms/op
                 createUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178137
  mean =      5.385 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 87111 
    [ 5.000,  7.500) = 79847 
    [ 7.500, 10.000) = 8917 
    [10.000, 12.500) = 1547 
    [12.500, 15.000) = 427 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      7.815 ms/op
     p(99.0000) =     10.463 ms/op
     p(99.9000) =     23.101 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     33.700 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 16.661 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.864 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.371 ±(99.9%) 0.020 ms/op
Iteration   1: 5.341 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   4.915 ms/op
                 existUser·p0.90:   6.783 ms/op
                 existUser·p0.95:   7.700 ms/op
                 existUser·p0.99:   10.732 ms/op
                 existUser·p0.999:  15.471 ms/op
                 existUser·p0.9999: 29.165 ms/op
                 existUser·p1.00:   29.950 ms/op

Iteration   2: 5.168 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.603 ms/op
                 existUser·p0.95:   7.651 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  24.252 ms/op
                 existUser·p0.9999: 29.839 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   3: 5.313 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.931 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.930 ms/op
                 existUser·p0.95:   7.946 ms/op
                 existUser·p0.99:   11.305 ms/op
                 existUser·p0.999:  24.568 ms/op
                 existUser·p0.9999: 28.933 ms/op
                 existUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181986
  mean =      5.273 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 103653 
    [ 5.000,  7.500) = 67233 
    [ 7.500, 10.000) = 8566 
    [10.000, 12.500) = 1567 
    [12.500, 15.000) = 564 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     29.570 ms/op
     p(99.9990) =     31.460 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 21.178 ±(99.9%) 0.357 ms/op
# Warmup Iteration   2: 7.227 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.808 ±(99.9%) 0.022 ms/op
Iteration   1: 5.962 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.089 ms/op
                 getUser·p0.50:   5.644 ms/op
                 getUser·p0.90:   7.512 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   11.796 ms/op
                 getUser·p0.999:  22.098 ms/op
                 getUser·p0.9999: 40.609 ms/op
                 getUser·p1.00:   41.550 ms/op

Iteration   2: 5.722 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.740 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   7.635 ms/op
                 getUser·p0.95:   8.962 ms/op
                 getUser·p0.99:   11.796 ms/op
                 getUser·p0.999:  22.221 ms/op
                 getUser·p0.9999: 29.100 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 5.327 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  26.205 ms/op
                 getUser·p0.9999: 38.862 ms/op
                 getUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169566
  mean =      5.658 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 64582 
    [ 5.000, 10.000) = 101334 
    [10.000, 15.000) = 3132 
    [15.000, 20.000) = 243 
    [20.000, 25.000) = 142 
    [25.000, 30.000) = 76 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     23.364 ms/op
     p(99.9900) =     38.601 ms/op
     p(99.9990) =     41.140 ms/op
     p(99.9999) =     41.550 ms/op
    p(100.0000) =     41.550 ms/op


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
# Warmup Iteration   1: 19.098 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 7.784 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.532 ±(99.9%) 0.029 ms/op
Iteration   1: 6.477 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   13.320 ms/op
                 listUser·p0.999:  27.296 ms/op
                 listUser·p0.9999: 30.555 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   2: 6.063 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  28.576 ms/op
                 listUser·p0.9999: 42.741 ms/op
                 listUser·p1.00:   45.285 ms/op

Iteration   3: 6.992 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   9.798 ms/op
                 listUser·p0.95:   11.264 ms/op
                 listUser·p0.99:   14.516 ms/op
                 listUser·p0.999:  28.783 ms/op
                 listUser·p0.9999: 32.159 ms/op
                 listUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147944
  mean =      6.489 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12386 
    [ 5.000, 10.000) = 127696 
    [10.000, 15.000) = 7051 
    [15.000, 20.000) = 462 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 224 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.302 ms/op
     p(50.0000) =      5.906 ms/op
     p(90.0000) =      8.634 ms/op
     p(95.0000) =     10.142 ms/op
     p(99.0000) =     13.697 ms/op
     p(99.9000) =     28.017 ms/op
     p(99.9900) =     41.039 ms/op
     p(99.9990) =     45.160 ms/op
     p(99.9999) =     45.285 ms/op
    p(100.0000) =     45.285 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.608 ± 2.701  ops/ms
ClientPb.existUser                       thrpt       3   5.721 ± 2.509  ops/ms
ClientPb.getUser                         thrpt       3   5.765 ± 3.766  ops/ms
ClientPb.listUser                        thrpt       3   4.864 ± 1.406  ops/ms
ClientPb.createUser                       avgt       3   5.812 ± 2.737   ms/op
ClientPb.existUser                        avgt       3   5.418 ± 1.544   ms/op
ClientPb.getUser                          avgt       3   5.682 ± 4.980   ms/op
ClientPb.listUser                         avgt       3   6.192 ± 1.208   ms/op
ClientPb.createUser                     sample  178137   5.385 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.233           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.815           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.463           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.101           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.490           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  181986   5.273 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.515           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.783           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.774           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.748           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.612           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.570           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.621           ms/op
ClientPb.getUser                        sample  169566   5.658 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.876           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.405           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.485           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.364           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.601           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.550           ms/op
ClientPb.listUser                       sample  147944   6.489 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.302           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.906           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.634           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.142           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.697           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.017           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.039           ms/op
ClientPb.listUser:listUser·p1.00        sample          45.285           ms/op
