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
# Warmup Iteration   1: 2.566 ops/ms
# Warmup Iteration   2: 6.691 ops/ms
# Warmup Iteration   3: 9.202 ops/ms
Iteration   1: 9.861 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.857 ±(99.9%) 2.447 ops/ms [Average]
  (min, avg, max) = (9.720, 9.857, 9.989), stdev = 0.134
  CI (99.9%): [7.409, 12.304] (assumes normal distribution)


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
# Warmup Iteration   1: 3.672 ops/ms
# Warmup Iteration   2: 9.045 ops/ms
# Warmup Iteration   3: 9.997 ops/ms
Iteration   1: 10.520 ops/ms
Iteration   2: 10.059 ops/ms
Iteration   3: 10.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.214 ±(99.9%) 4.837 ops/ms [Average]
  (min, avg, max) = (10.059, 10.214, 10.520), stdev = 0.265
  CI (99.9%): [5.377, 15.051] (assumes normal distribution)


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
# Warmup Iteration   1: 3.595 ops/ms
# Warmup Iteration   2: 9.409 ops/ms
# Warmup Iteration   3: 9.623 ops/ms
Iteration   1: 10.350 ops/ms
Iteration   2: 10.316 ops/ms
Iteration   3: 9.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.170 ±(99.9%) 5.167 ops/ms [Average]
  (min, avg, max) = (9.844, 10.170, 10.350), stdev = 0.283
  CI (99.9%): [5.004, 15.337] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ops/ms
# Warmup Iteration   2: 7.479 ops/ms
# Warmup Iteration   3: 8.483 ops/ms
Iteration   1: 8.485 ops/ms
Iteration   2: 8.759 ops/ms
Iteration   3: 8.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.683 ±(99.9%) 3.153 ops/ms [Average]
  (min, avg, max) = (8.485, 8.683, 8.804), stdev = 0.173
  CI (99.9%): [5.530, 11.836] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.312 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.005 ms/op
Iteration   1: 3.340 ±(99.9%) 0.004 ms/op
Iteration   2: 3.100 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.170 ±(99.9%) 2.684 ms/op [Average]
  (min, avg, max) = (3.072, 3.170, 3.340), stdev = 0.147
  CI (99.9%): [0.487, 5.854] (assumes normal distribution)


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
# Warmup Iteration   1: 7.007 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.004 ms/op
Iteration   1: 3.151 ±(99.9%) 0.006 ms/op
Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
Iteration   3: 3.199 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.147 ±(99.9%) 0.985 ms/op [Average]
  (min, avg, max) = (3.092, 3.147, 3.199), stdev = 0.054
  CI (99.9%): [2.162, 4.133] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 6.769 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.002 ms/op
Iteration   1: 3.225 ±(99.9%) 0.004 ms/op
Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
Iteration   3: 3.222 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.193 ±(99.9%) 0.960 ms/op [Average]
  (min, avg, max) = (3.133, 3.193, 3.225), stdev = 0.053
  CI (99.9%): [2.234, 4.153] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.279 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.004 ms/op
Iteration   1: 3.748 ±(99.9%) 0.006 ms/op
Iteration   2: 3.682 ±(99.9%) 0.008 ms/op
Iteration   3: 3.735 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (3.682, 3.722, 3.748), stdev = 0.035
  CI (99.9%): [3.085, 4.358] (assumes normal distribution)


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
# Warmup Iteration   1: 7.664 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
Iteration   1: 3.196 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 19.366 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.494 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 21.605 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.282 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  15.017 ms/op
                 createUser·p0.9999: 18.116 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303679
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22042 
    [ 2.500,  5.000) = 276967 
    [ 5.000,  7.500) = 3833 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     19.813 ms/op
     p(99.9990) =     22.739 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.622 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.153 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.014 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 20.040 ms/op
                 existUser·p1.00:   20.513 ms/op

Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  11.626 ms/op
                 existUser·p0.9999: 25.263 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  9.257 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304919
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24735 
    [ 2.500,  5.000) = 274515 
    [ 5.000,  7.500) = 4940 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     11.355 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     25.525 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 7.384 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.010 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 20.324 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  9.630 ms/op
                 getUser·p0.9999: 20.328 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   3: 3.134 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 28.888 ms/op
                 getUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304704
  mean =      3.149 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14640 
    [ 2.500,  5.000) = 284219 
    [ 5.000,  7.500) = 4989 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.090 ms/op
     p(99.9900) =     27.510 ms/op
     p(99.9990) =     29.685 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 9.085 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.012 ms/op
Iteration   1: 3.826 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   5.213 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  17.168 ms/op
                 listUser·p0.9999: 22.127 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.725 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 14.661 ms/op
                 listUser·p1.00:   15.254 ms/op

Iteration   3: 3.666 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   3.981 ms/op
                 listUser·p0.99:   6.264 ms/op
                 listUser·p0.999:  12.288 ms/op
                 listUser·p0.9999: 13.489 ms/op
                 listUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256727
  mean =      3.738 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 248763 
    [ 5.000,  7.500) = 5770 
    [ 7.500, 10.000) = 1475 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     20.982 ms/op
     p(99.9990) =     22.828 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.857 ± 2.447  ops/ms
ClientPb.existUser                       thrpt       3  10.214 ± 4.837  ops/ms
ClientPb.getUser                         thrpt       3  10.170 ± 5.167  ops/ms
ClientPb.listUser                        thrpt       3   8.683 ± 3.153  ops/ms
ClientPb.createUser                       avgt       3   3.170 ± 2.684   ms/op
ClientPb.existUser                        avgt       3   3.147 ± 0.985   ms/op
ClientPb.getUser                          avgt       3   3.193 ± 0.960   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 0.637   ms/op
ClientPb.createUser                     sample  303679   3.160 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.282           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.839           ms/op
ClientPb.existUser                      sample  304919   3.147 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.802           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.355           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.888           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.051           ms/op
ClientPb.getUser                        sample  304704   3.149 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.004           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.090           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.510           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.409           ms/op
ClientPb.listUser                       sample  256727   3.738 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.484           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.982           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.364           ms/op
