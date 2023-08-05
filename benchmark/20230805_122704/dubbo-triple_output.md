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
# Warmup Iteration   1: 1.758 ops/ms
# Warmup Iteration   2: 3.715 ops/ms
# Warmup Iteration   3: 6.186 ops/ms
Iteration   1: 7.789 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.959 ±(99.9%) 2.689 ops/ms [Average]
  (min, avg, max) = (7.789, 7.959, 8.048), stdev = 0.147
  CI (99.9%): [5.270, 10.648] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.669 ops/ms
# Warmup Iteration   2: 7.650 ops/ms
# Warmup Iteration   3: 8.524 ops/ms
Iteration   1: 8.515 ops/ms
Iteration   2: 8.555 ops/ms
Iteration   3: 8.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.587 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (8.515, 8.587, 8.690), stdev = 0.092
  CI (99.9%): [6.917, 10.256] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.456 ops/ms
# Warmup Iteration   2: 7.426 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.407 ops/ms
Iteration   2: 8.358 ops/ms
Iteration   3: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.445 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (8.358, 8.445, 8.570), stdev = 0.111
  CI (99.9%): [6.417, 10.473] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.182 ops/ms
# Warmup Iteration   2: 5.772 ops/ms
# Warmup Iteration   3: 6.846 ops/ms
Iteration   1: 6.792 ops/ms
Iteration   2: 7.179 ops/ms
Iteration   3: 7.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.051 ±(99.9%) 4.092 ops/ms [Average]
  (min, avg, max) = (6.792, 7.051, 7.182), stdev = 0.224
  CI (99.9%): [2.959, 11.143] (assumes normal distribution)


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
# Warmup Iteration   1: 11.415 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.002 ms/op
Iteration   1: 3.792 ±(99.9%) 0.010 ms/op
Iteration   2: 3.828 ±(99.9%) 0.006 ms/op
Iteration   3: 3.778 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.800 ±(99.9%) 0.466 ms/op [Average]
  (min, avg, max) = (3.778, 3.800, 3.828), stdev = 0.026
  CI (99.9%): [3.334, 4.265] (assumes normal distribution)


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
# Warmup Iteration   1: 9.920 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.004 ms/op
Iteration   1: 3.666 ±(99.9%) 0.004 ms/op
Iteration   2: 3.663 ±(99.9%) 0.011 ms/op
Iteration   3: 3.579 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.636 ±(99.9%) 0.906 ms/op [Average]
  (min, avg, max) = (3.579, 3.636, 3.666), stdev = 0.050
  CI (99.9%): [2.730, 4.542] (assumes normal distribution)


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
# Warmup Iteration   1: 11.729 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.011 ms/op
Iteration   1: 3.964 ±(99.9%) 0.007 ms/op
Iteration   2: 3.896 ±(99.9%) 0.005 ms/op
Iteration   3: 3.828 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.896 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.828, 3.896, 3.964), stdev = 0.068
  CI (99.9%): [2.660, 5.132] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.880 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.406 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.635 ±(99.9%) 0.010 ms/op
Iteration   1: 4.434 ±(99.9%) 0.009 ms/op
Iteration   2: 4.481 ±(99.9%) 0.008 ms/op
Iteration   3: 4.591 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.502 ±(99.9%) 1.473 ms/op [Average]
  (min, avg, max) = (4.434, 4.502, 4.591), stdev = 0.081
  CI (99.9%): [3.029, 5.975] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.136 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.910 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.019 ms/op
Iteration   1: 3.809 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  12.583 ms/op
                 createUser·p0.9999: 25.762 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 3.814 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  27.230 ms/op
                 createUser·p0.9999: 38.535 ms/op
                 createUser·p1.00:   39.780 ms/op

Iteration   3: 3.898 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   7.853 ms/op
                 createUser·p0.999:  26.247 ms/op
                 createUser·p0.9999: 33.416 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 250000
  mean =      3.840 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1740 
    [ 2.500,  5.000) = 236700 
    [ 5.000,  7.500) = 9256 
    [ 7.500, 10.000) = 1516 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     39.518 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.774 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.010 ms/op
Iteration   1: 3.745 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.513 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  23.305 ms/op
                 existUser·p0.9999: 27.192 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   2: 3.794 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   5.144 ms/op
                 existUser·p0.99:   7.602 ms/op
                 existUser·p0.999:  12.447 ms/op
                 existUser·p0.9999: 26.715 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 3.696 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  26.918 ms/op
                 existUser·p0.9999: 30.605 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 256358
  mean =      3.745 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1468 
    [ 2.500,  5.000) = 242784 
    [ 5.000,  7.500) = 9882 
    [ 7.500, 10.000) = 1490 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     20.461 ms/op
     p(99.9900) =     29.855 ms/op
     p(99.9990) =     30.882 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.738 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.013 ms/op
Iteration   1: 3.838 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.741 ms/op
                 getUser·p0.999:  13.468 ms/op
                 getUser·p0.9999: 21.285 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   2: 3.898 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.456 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   8.053 ms/op
                 getUser·p0.999:  18.771 ms/op
                 getUser·p0.9999: 23.998 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 3.982 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.559 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 26.503 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245910
  mean =      3.905 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 685 
    [ 2.500,  5.000) = 230870 
    [ 5.000,  7.500) = 11107 
    [ 7.500, 10.000) = 2599 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     13.600 ms/op
     p(99.9900) =     25.730 ms/op
     p(99.9990) =     26.988 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.600 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.163 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.609 ±(99.9%) 0.016 ms/op
Iteration   1: 4.631 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.948 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   9.118 ms/op
                 listUser·p0.999:  23.821 ms/op
                 listUser·p0.9999: 26.433 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   2: 4.511 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.905 ms/op
                 listUser·p0.99:   9.106 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 20.050 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.668 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 40.501 ms/op
                 listUser·p1.00:   41.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208478
  mean =      4.602 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 180786 
    [ 5.000, 10.000) = 26052 
    [10.000, 15.000) = 1218 
    [15.000, 20.000) = 212 
    [20.000, 25.000) = 145 
    [25.000, 30.000) = 43 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     33.695 ms/op
     p(99.9990) =     41.026 ms/op
     p(99.9999) =     41.157 ms/op
    p(100.0000) =     41.157 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.959 ± 2.689  ops/ms
ClientPb.existUser                       thrpt       3   8.587 ± 1.669  ops/ms
ClientPb.getUser                         thrpt       3   8.445 ± 2.028  ops/ms
ClientPb.listUser                        thrpt       3   7.051 ± 4.092  ops/ms
ClientPb.createUser                       avgt       3   3.800 ± 0.466   ms/op
ClientPb.existUser                        avgt       3   3.636 ± 0.906   ms/op
ClientPb.getUser                          avgt       3   3.896 ± 1.236   ms/op
ClientPb.listUser                         avgt       3   4.502 ± 1.473   ms/op
ClientPb.createUser                     sample  250000   3.840 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.028           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.340           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.248           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.603           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.780           ms/op
ClientPb.existUser                      sample  256358   3.745 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.513           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.461           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.855           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  245910   3.905 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.456           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.815           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.600           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099           ms/op
ClientPb.listUser                       sample  208478   4.602 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.796           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.322           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.087           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.695           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.157           ms/op
