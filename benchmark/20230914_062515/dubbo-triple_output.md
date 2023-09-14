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
# Warmup Iteration   1: 2.074 ops/ms
# Warmup Iteration   2: 5.542 ops/ms
# Warmup Iteration   3: 8.756 ops/ms
Iteration   1: 9.289 ops/ms
Iteration   2: 9.232 ops/ms
Iteration   3: 9.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.211 ±(99.9%) 1.640 ops/ms [Average]
  (min, avg, max) = (9.113, 9.211, 9.289), stdev = 0.090
  CI (99.9%): [7.571, 10.852] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.001 ops/ms
# Warmup Iteration   2: 8.841 ops/ms
# Warmup Iteration   3: 9.326 ops/ms
Iteration   1: 9.675 ops/ms
Iteration   2: 9.728 ops/ms
Iteration   3: 9.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.735 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (9.675, 9.735, 9.801), stdev = 0.063
  CI (99.9%): [8.578, 10.891] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.097 ops/ms
# Warmup Iteration   2: 8.356 ops/ms
# Warmup Iteration   3: 9.054 ops/ms
Iteration   1: 9.167 ops/ms
Iteration   2: 9.456 ops/ms
Iteration   3: 9.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.340 ±(99.9%) 2.793 ops/ms [Average]
  (min, avg, max) = (9.167, 9.340, 9.456), stdev = 0.153
  CI (99.9%): [6.547, 12.134] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.990 ops/ms
# Warmup Iteration   2: 7.148 ops/ms
# Warmup Iteration   3: 7.526 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 7.739 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.828 ±(99.9%) 1.699 ops/ms [Average]
  (min, avg, max) = (7.739, 7.828, 7.925), stdev = 0.093
  CI (99.9%): [6.129, 9.527] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.947 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.725 ±(99.9%) 0.009 ms/op
Iteration   1: 3.556 ±(99.9%) 0.006 ms/op
Iteration   2: 3.426 ±(99.9%) 0.005 ms/op
Iteration   3: 3.504 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.495 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (3.426, 3.495, 3.556), stdev = 0.066
  CI (99.9%): [2.298, 4.693] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.111 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.006 ms/op
Iteration   1: 3.319 ±(99.9%) 0.005 ms/op
Iteration   2: 3.305 ±(99.9%) 0.003 ms/op
Iteration   3: 3.296 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.307 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (3.296, 3.307, 3.319), stdev = 0.011
  CI (99.9%): [3.100, 3.514] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.970 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.008 ms/op
Iteration   1: 3.500 ±(99.9%) 0.004 ms/op
Iteration   2: 3.528 ±(99.9%) 0.005 ms/op
Iteration   3: 3.519 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.516 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (3.500, 3.516, 3.528), stdev = 0.015
  CI (99.9%): [3.248, 3.783] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.758 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.010 ms/op
Iteration   1: 3.966 ±(99.9%) 0.006 ms/op
Iteration   2: 4.049 ±(99.9%) 0.009 ms/op
Iteration   3: 4.009 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.008 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.966, 4.008, 4.049), stdev = 0.041
  CI (99.9%): [3.253, 4.764] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.110 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.010 ms/op
Iteration   1: 3.716 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   5.841 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  18.317 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 3.503 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  20.134 ms/op
                 createUser·p0.9999: 27.839 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   3: 3.372 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.958 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  16.785 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272170
  mean =      3.525 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10178 
    [ 2.500,  5.000) = 250904 
    [ 5.000,  7.500) = 9389 
    [ 7.500, 10.000) = 1225 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     17.329 ms/op
     p(99.9900) =     26.404 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 8.892 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.008 ms/op
Iteration   1: 3.475 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  20.280 ms/op
                 existUser·p0.9999: 22.833 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.377 ms/op
                 existUser·p0.999:  15.864 ms/op
                 existUser·p0.9999: 25.341 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 27.456 ms/op
                 existUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282826
  mean =      3.392 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5432 
    [ 2.500,  5.000) = 270129 
    [ 5.000,  7.500) = 5675 
    [ 7.500, 10.000) = 1215 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     26.205 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 11.522 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.014 ms/op
Iteration   1: 3.621 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 23.114 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.543 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  22.313 ms/op
                 getUser·p0.9999: 31.719 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   3: 3.529 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  10.494 ms/op
                 getUser·p0.9999: 27.656 ms/op
                 getUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269048
  mean =      3.564 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2956 
    [ 2.500,  5.000) = 257441 
    [ 5.000,  7.500) = 6869 
    [ 7.500, 10.000) = 1222 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     20.382 ms/op
     p(99.9900) =     30.346 ms/op
     p(99.9990) =     32.259 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 11.910 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.014 ms/op
Iteration   1: 4.200 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  20.050 ms/op
                 listUser·p0.9999: 25.426 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   2: 4.182 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 26.280 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   3: 4.152 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.712 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 17.616 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229682
  mean =      4.178 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 217530 
    [ 5.000,  7.500) = 8723 
    [ 7.500, 10.000) = 2193 
    [10.000, 12.500) = 703 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      8.308 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.211 ± 1.640  ops/ms
ClientPb.existUser                       thrpt       3   9.735 ± 1.156  ops/ms
ClientPb.getUser                         thrpt       3   9.340 ± 2.793  ops/ms
ClientPb.listUser                        thrpt       3   7.828 ± 1.699  ops/ms
ClientPb.createUser                       avgt       3   3.495 ± 1.198   ms/op
ClientPb.existUser                        avgt       3   3.307 ± 0.207   ms/op
ClientPb.getUser                          avgt       3   3.516 ± 0.268   ms/op
ClientPb.listUser                         avgt       3   4.008 ± 0.755   ms/op
ClientPb.createUser                     sample  272170   3.525 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.505           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.053           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.329           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.404           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.590           ms/op
ClientPb.existUser                      sample  282826   3.392 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.546           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.121           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.205           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.475           ms/op
ClientPb.getUser                        sample  269048   3.564 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.061           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.668           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.382           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.346           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.440           ms/op
ClientPb.listUser                       sample  229682   4.178 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.054           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.308           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.695           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.297           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
