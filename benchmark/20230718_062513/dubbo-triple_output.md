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
# Warmup Iteration   1: 2.427 ops/ms
# Warmup Iteration   2: 6.335 ops/ms
# Warmup Iteration   3: 9.004 ops/ms
Iteration   1: 9.492 ops/ms
Iteration   2: 9.575 ops/ms
Iteration   3: 9.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.548 ±(99.9%) 0.877 ops/ms [Average]
  (min, avg, max) = (9.492, 9.548, 9.576), stdev = 0.048
  CI (99.9%): [8.671, 10.424] (assumes normal distribution)


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
# Warmup Iteration   1: 3.483 ops/ms
# Warmup Iteration   2: 9.363 ops/ms
# Warmup Iteration   3: 10.196 ops/ms
Iteration   1: 10.136 ops/ms
Iteration   2: 10.172 ops/ms
Iteration   3: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.135 ±(99.9%) 0.680 ops/ms [Average]
  (min, avg, max) = (10.098, 10.135, 10.172), stdev = 0.037
  CI (99.9%): [9.455, 10.816] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.363 ops/ms
# Warmup Iteration   2: 8.204 ops/ms
# Warmup Iteration   3: 9.721 ops/ms
Iteration   1: 9.652 ops/ms
Iteration   2: 9.622 ops/ms
Iteration   3: 9.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.712 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (9.622, 9.712, 9.864), stdev = 0.132
  CI (99.9%): [7.306, 12.119] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.062 ops/ms
# Warmup Iteration   2: 7.821 ops/ms
# Warmup Iteration   3: 8.372 ops/ms
Iteration   1: 8.470 ops/ms
Iteration   2: 8.287 ops/ms
Iteration   3: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.390 ±(99.9%) 1.715 ops/ms [Average]
  (min, avg, max) = (8.287, 8.390, 8.470), stdev = 0.094
  CI (99.9%): [6.675, 10.106] (assumes normal distribution)


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
# Warmup Iteration   1: 9.360 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.008 ms/op
Iteration   1: 3.375 ±(99.9%) 0.006 ms/op
Iteration   2: 3.263 ±(99.9%) 0.007 ms/op
Iteration   3: 3.268 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.302 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.263, 3.302, 3.375), stdev = 0.063
  CI (99.9%): [2.149, 4.455] (assumes normal distribution)


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
# Warmup Iteration   1: 7.252 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.005 ms/op
Iteration   1: 3.094 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
Iteration   3: 3.173 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.154 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.094, 3.154, 3.195), stdev = 0.053
  CI (99.9%): [2.180, 4.127] (assumes normal distribution)


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
# Warmup Iteration   1: 8.850 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.006 ms/op
Iteration   1: 3.284 ±(99.9%) 0.004 ms/op
Iteration   2: 3.283 ±(99.9%) 0.006 ms/op
Iteration   3: 3.146 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.238 ±(99.9%) 1.450 ms/op [Average]
  (min, avg, max) = (3.146, 3.238, 3.284), stdev = 0.079
  CI (99.9%): [1.788, 4.687] (assumes normal distribution)


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
# Warmup Iteration   1: 9.383 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.009 ms/op
Iteration   1: 3.735 ±(99.9%) 0.009 ms/op
Iteration   2: 3.742 ±(99.9%) 0.009 ms/op
Iteration   3: 3.686 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.721 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.686, 3.721, 3.742), stdev = 0.030
  CI (99.9%): [3.166, 4.277] (assumes normal distribution)


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
# Warmup Iteration   1: 8.586 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.010 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  16.578 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  14.575 ms/op
                 createUser·p0.9999: 23.735 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.262 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  20.218 ms/op
                 createUser·p0.9999: 30.570 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291099
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24341 
    [ 2.500,  5.000) = 261090 
    [ 5.000,  7.500) = 4789 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     19.330 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     33.626 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 8.648 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.189 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.702 ms/op
                 existUser·p0.9999: 19.593 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.494 ms/op
                 existUser·p0.999:  13.555 ms/op
                 existUser·p0.9999: 23.490 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  13.553 ms/op
                 existUser·p0.9999: 21.058 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305522
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6993 
    [ 2.500,  5.000) = 293756 
    [ 5.000,  7.500) = 3958 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      5.479 ms/op
     p(99.9000) =     13.402 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     24.083 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 7.493 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.012 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.520 ms/op
                 getUser·p0.999:  15.073 ms/op
                 getUser·p0.9999: 19.929 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  11.872 ms/op
                 getUser·p0.9999: 28.213 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.636 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  15.057 ms/op
                 getUser·p0.9999: 26.348 ms/op
                 getUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290405
  mean =      3.303 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9872 
    [ 2.500,  5.000) = 273600 
    [ 5.000,  7.500) = 5985 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     15.044 ms/op
     p(99.9900) =     27.125 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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
# Warmup Iteration   1: 8.404 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
Iteration   1: 3.891 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  16.695 ms/op
                 listUser·p0.9999: 19.966 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.725 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  14.455 ms/op
                 listUser·p0.9999: 19.684 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252525
  mean =      3.799 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 244442 
    [ 5.000,  7.500) = 5764 
    [ 7.500, 10.000) = 1608 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.167 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     14.589 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.294 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.548 ± 0.877  ops/ms
ClientPb.existUser                       thrpt       3  10.135 ± 0.680  ops/ms
ClientPb.getUser                         thrpt       3   9.712 ± 2.407  ops/ms
ClientPb.listUser                        thrpt       3   8.390 ± 1.715  ops/ms
ClientPb.createUser                       avgt       3   3.302 ± 1.153   ms/op
ClientPb.existUser                        avgt       3   3.154 ± 0.974   ms/op
ClientPb.getUser                          avgt       3   3.238 ± 1.450   ms/op
ClientPb.listUser                         avgt       3   3.721 ± 0.555   ms/op
ClientPb.createUser                     sample  291099   3.296 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.063           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.330           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.461           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  305522   3.142 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.479           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.402           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.577           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.084           ms/op
ClientPb.getUser                        sample  290405   3.303 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.386           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.044           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.125           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  252525   3.799 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.167           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.589           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
