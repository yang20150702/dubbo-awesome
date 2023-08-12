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
# Warmup Iteration   1: 1.593 ops/ms
# Warmup Iteration   2: 3.769 ops/ms
# Warmup Iteration   3: 6.953 ops/ms
Iteration   1: 7.425 ops/ms
Iteration   2: 7.544 ops/ms
Iteration   3: 7.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.526 ±(99.9%) 1.705 ops/ms [Average]
  (min, avg, max) = (7.425, 7.526, 7.609), stdev = 0.093
  CI (99.9%): [5.821, 9.231] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.260 ops/ms
# Warmup Iteration   2: 6.741 ops/ms
# Warmup Iteration   3: 8.017 ops/ms
Iteration   1: 8.304 ops/ms
Iteration   2: 8.109 ops/ms
Iteration   3: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.254 ±(99.9%) 2.327 ops/ms [Average]
  (min, avg, max) = (8.109, 8.254, 8.349), stdev = 0.128
  CI (99.9%): [5.927, 10.581] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.148 ops/ms
# Warmup Iteration   2: 6.673 ops/ms
# Warmup Iteration   3: 7.030 ops/ms
Iteration   1: 7.129 ops/ms
Iteration   2: 7.698 ops/ms
Iteration   3: 7.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.568 ±(99.9%) 7.108 ops/ms [Average]
  (min, avg, max) = (7.129, 7.568, 7.875), stdev = 0.390
  CI (99.9%): [0.460, 14.675] (assumes normal distribution)


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
# Warmup Iteration   1: 1.999 ops/ms
# Warmup Iteration   2: 5.215 ops/ms
# Warmup Iteration   3: 6.515 ops/ms
Iteration   1: 6.168 ops/ms
Iteration   2: 6.830 ops/ms
Iteration   3: 6.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.570 ±(99.9%) 6.443 ops/ms [Average]
  (min, avg, max) = (6.168, 6.570, 6.830), stdev = 0.353
  CI (99.9%): [0.127, 13.013] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.672 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.941 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.370 ±(99.9%) 0.008 ms/op
Iteration   1: 4.010 ±(99.9%) 0.005 ms/op
Iteration   2: 3.949 ±(99.9%) 0.008 ms/op
Iteration   3: 4.189 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.049 ±(99.9%) 2.271 ms/op [Average]
  (min, avg, max) = (3.949, 4.049, 4.189), stdev = 0.124
  CI (99.9%): [1.778, 6.320] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.682 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.006 ms/op
Iteration   1: 4.002 ±(99.9%) 0.005 ms/op
Iteration   2: 3.849 ±(99.9%) 0.003 ms/op
Iteration   3: 3.956 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.936 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (3.849, 3.936, 4.002), stdev = 0.078
  CI (99.9%): [2.506, 5.367] (assumes normal distribution)


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
# Warmup Iteration   1: 12.980 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.113 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.007 ms/op
Iteration   1: 4.177 ±(99.9%) 0.008 ms/op
Iteration   2: 3.943 ±(99.9%) 0.009 ms/op
Iteration   3: 4.558 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.226 ±(99.9%) 5.666 ms/op [Average]
  (min, avg, max) = (3.943, 4.226, 4.558), stdev = 0.311
  CI (99.9%): [≈ 0, 9.892] (assumes normal distribution)


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
# Warmup Iteration   1: 15.948 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.816 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.862 ±(99.9%) 0.007 ms/op
Iteration   1: 4.969 ±(99.9%) 0.006 ms/op
Iteration   2: 4.868 ±(99.9%) 0.014 ms/op
Iteration   3: 4.766 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.868 ±(99.9%) 1.853 ms/op [Average]
  (min, avg, max) = (4.766, 4.868, 4.969), stdev = 0.102
  CI (99.9%): [3.015, 6.721] (assumes normal distribution)


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
# Warmup Iteration   1: 12.899 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 5.736 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.022 ms/op
Iteration   1: 4.104 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.659 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   8.290 ms/op
                 createUser·p0.999:  25.526 ms/op
                 createUser·p0.9999: 29.367 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   2: 4.027 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   7.174 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 32.350 ms/op
                 createUser·p1.00:   32.801 ms/op

Iteration   3: 4.209 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.935 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  19.290 ms/op
                 createUser·p0.9999: 31.470 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233479
  mean =      4.112 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 250 
    [ 2.500,  5.000) = 214948 
    [ 5.000,  7.500) = 15088 
    [ 7.500, 10.000) = 2306 
    [10.000, 12.500) = 468 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     23.577 ms/op
     p(99.9900) =     31.479 ms/op
     p(99.9990) =     32.626 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 12.258 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.015 ms/op
Iteration   1: 3.798 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   7.283 ms/op
                 existUser·p0.999:  23.233 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.789 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  12.085 ms/op
                 existUser·p0.9999: 34.669 ms/op
                 existUser·p1.00:   36.110 ms/op

Iteration   3: 3.964 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  26.751 ms/op
                 existUser·p0.9999: 30.374 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249312
  mean =      3.849 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 264 
    [ 2.500,  5.000) = 237612 
    [ 5.000,  7.500) = 9454 
    [ 7.500, 10.000) = 1213 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     22.950 ms/op
     p(99.9900) =     33.887 ms/op
     p(99.9990) =     35.326 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 13.415 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.014 ms/op
Iteration   1: 4.139 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   9.370 ms/op
                 getUser·p0.999:  24.864 ms/op
                 getUser·p0.9999: 28.690 ms/op
                 getUser·p1.00:   33.030 ms/op

Iteration   2: 3.898 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  13.155 ms/op
                 getUser·p0.9999: 34.851 ms/op
                 getUser·p1.00:   36.438 ms/op

Iteration   3: 4.066 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   8.038 ms/op
                 getUser·p0.999:  25.586 ms/op
                 getUser·p0.9999: 32.131 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237896
  mean =      4.032 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 220565 
    [ 5.000,  7.500) = 13631 
    [ 7.500, 10.000) = 2311 
    [10.000, 12.500) = 835 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     23.829 ms/op
     p(99.9900) =     34.224 ms/op
     p(99.9990) =     36.339 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 12.577 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 5.429 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.062 ±(99.9%) 0.019 ms/op
Iteration   1: 4.810 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.666 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  27.169 ms/op
                 listUser·p0.9999: 29.983 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 5.017 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  18.743 ms/op
                 listUser·p0.9999: 21.504 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 4.667 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.173 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198620
  mean =      4.827 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 149032 
    [ 5.000,  7.500) = 43207 
    [ 7.500, 10.000) = 4801 
    [10.000, 12.500) = 835 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.011 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     29.135 ms/op
     p(99.9990) =     30.411 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.526 ± 1.705  ops/ms
ClientPb.existUser                       thrpt       3   8.254 ± 2.327  ops/ms
ClientPb.getUser                         thrpt       3   7.568 ± 7.108  ops/ms
ClientPb.listUser                        thrpt       3   6.570 ± 6.443  ops/ms
ClientPb.createUser                       avgt       3   4.049 ± 2.271   ms/op
ClientPb.existUser                        avgt       3   3.936 ± 1.430   ms/op
ClientPb.getUser                          avgt       3   4.226 ± 5.666   ms/op
ClientPb.listUser                         avgt       3   4.868 ± 1.853   ms/op
ClientPb.createUser                     sample  233479   4.112 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.509           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.086           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.577           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.479           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.801           ms/op
ClientPb.existUser                      sample  249312   3.849 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.251           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.184           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.950           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.887           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.110           ms/op
ClientPb.getUser                        sample  237896   4.032 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.423           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.503           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.829           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.224           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438           ms/op
ClientPb.listUser                       sample  198620   4.827 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.011           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.242           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.388           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.021           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.135           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.605           ms/op
