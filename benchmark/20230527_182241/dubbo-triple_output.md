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
# Warmup Iteration   1: 2.567 ops/ms
# Warmup Iteration   2: 6.072 ops/ms
# Warmup Iteration   3: 9.500 ops/ms
Iteration   1: 10.041 ops/ms
Iteration   2: 10.034 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.086 ±(99.9%) 1.519 ops/ms [Average]
  (min, avg, max) = (10.034, 10.086, 10.182), stdev = 0.083
  CI (99.9%): [8.567, 11.604] (assumes normal distribution)


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
# Warmup Iteration   1: 3.901 ops/ms
# Warmup Iteration   2: 9.180 ops/ms
# Warmup Iteration   3: 10.307 ops/ms
Iteration   1: 10.022 ops/ms
Iteration   2: 10.106 ops/ms
Iteration   3: 10.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.200 ±(99.9%) 4.376 ops/ms [Average]
  (min, avg, max) = (10.022, 10.200, 10.473), stdev = 0.240
  CI (99.9%): [5.824, 14.576] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ops/ms
# Warmup Iteration   2: 8.821 ops/ms
# Warmup Iteration   3: 9.574 ops/ms
Iteration   1: 9.746 ops/ms
Iteration   2: 9.791 ops/ms
Iteration   3: 9.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.806 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (9.746, 9.806, 9.882), stdev = 0.069
  CI (99.9%): [8.539, 11.074] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 7.696 ops/ms
# Warmup Iteration   3: 8.181 ops/ms
Iteration   1: 8.194 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.348 ±(99.9%) 2.653 ops/ms [Average]
  (min, avg, max) = (8.194, 8.348, 8.483), stdev = 0.145
  CI (99.9%): [5.696, 11.001] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.155 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.008 ms/op
Iteration   2: 3.187 ±(99.9%) 0.006 ms/op
Iteration   3: 3.160 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.153 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (3.111, 3.153, 3.187), stdev = 0.038
  CI (99.9%): [2.451, 3.855] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.988 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.005 ms/op
Iteration   1: 3.097 ±(99.9%) 0.004 ms/op
Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.111 ±(99.9%) 1.785 ms/op [Average]
  (min, avg, max) = (3.020, 3.111, 3.214), stdev = 0.098
  CI (99.9%): [1.326, 4.895] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.169 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.003 ms/op
Iteration   1: 3.188 ±(99.9%) 0.004 ms/op
Iteration   2: 3.261 ±(99.9%) 0.005 ms/op
Iteration   3: 3.155 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.202 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.155, 3.202, 3.261), stdev = 0.054
  CI (99.9%): [2.214, 4.190] (assumes normal distribution)


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
# Warmup Iteration   1: 8.298 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.005 ms/op
Iteration   1: 3.847 ±(99.9%) 0.003 ms/op
Iteration   2: 3.658 ±(99.9%) 0.010 ms/op
Iteration   3: 3.766 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (3.658, 3.757, 3.847), stdev = 0.095
  CI (99.9%): [2.029, 5.486] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.730 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.011 ms/op
Iteration   1: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  13.222 ms/op
                 createUser·p0.9999: 22.025 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  14.615 ms/op
                 createUser·p0.9999: 22.342 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.234 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  18.866 ms/op
                 createUser·p0.9999: 28.086 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299146
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29763 
    [ 2.500,  5.000) = 262744 
    [ 5.000,  7.500) = 5573 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     17.972 ms/op
     p(99.9900) =     25.835 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 6.445 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.008 ms/op
Iteration   1: 3.058 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.380 ms/op
                 existUser·p0.999:  9.515 ms/op
                 existUser·p0.9999: 20.714 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   2: 3.017 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.301 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  11.407 ms/op
                 existUser·p0.9999: 22.525 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.297 ms/op
                 existUser·p0.999:  15.388 ms/op
                 existUser·p0.9999: 20.333 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315508
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18615 
    [ 2.500,  5.000) = 292437 
    [ 5.000,  7.500) = 3887 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.449 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     14.499 ms/op
     p(99.9900) =     21.609 ms/op
     p(99.9990) =     23.000 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 7.973 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.457 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.011 ms/op
Iteration   1: 3.218 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  18.299 ms/op
                 getUser·p0.9999: 23.529 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.259 ms/op
                 getUser·p0.999:  8.921 ms/op
                 getUser·p0.9999: 22.807 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 3.308 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  13.902 ms/op
                 getUser·p0.9999: 22.730 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294700
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21102 
    [ 2.500,  5.000) = 265433 
    [ 5.000,  7.500) = 7267 
    [ 7.500, 10.000) = 526 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     23.795 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 8.804 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.013 ms/op
Iteration   1: 3.792 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 20.105 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   2: 3.865 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.519 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 15.249 ms/op
                 listUser·p1.00:   16.187 ms/op

Iteration   3: 3.801 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  11.977 ms/op
                 listUser·p0.9999: 13.255 ms/op
                 listUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251276
  mean =      3.819 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 243812 
    [ 5.000,  7.500) = 5400 
    [ 7.500, 10.000) = 1233 
    [10.000, 12.500) = 452 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     20.725 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.086 ± 1.519  ops/ms
ClientPb.existUser                       thrpt       3  10.200 ± 4.376  ops/ms
ClientPb.getUser                         thrpt       3   9.806 ± 1.268  ops/ms
ClientPb.listUser                        thrpt       3   8.348 ± 2.653  ops/ms
ClientPb.createUser                       avgt       3   3.153 ± 0.702   ms/op
ClientPb.existUser                        avgt       3   3.111 ± 1.785   ms/op
ClientPb.getUser                          avgt       3   3.202 ± 0.988   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 1.729   ms/op
ClientPb.createUser                     sample  299146   3.208 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.972           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.835           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  315508   3.040 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.499           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.609           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.134           ms/op
ClientPb.getUser                        sample  294700   3.257 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.923           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.186           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.134           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.986           ms/op
ClientPb.listUser                       sample  251276   3.819 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.519           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.140           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.103           ms/op
