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
# Warmup Iteration   1: 1.105 ops/ms
# Warmup Iteration   2: 2.423 ops/ms
# Warmup Iteration   3: 5.225 ops/ms
Iteration   1: 5.534 ops/ms
Iteration   2: 5.701 ops/ms
Iteration   3: 5.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.685 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (5.534, 5.685, 5.818), stdev = 0.143
  CI (99.9%): [3.080, 8.289] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.639 ops/ms
# Warmup Iteration   2: 4.224 ops/ms
# Warmup Iteration   3: 6.022 ops/ms
Iteration   1: 6.286 ops/ms
Iteration   2: 6.085 ops/ms
Iteration   3: 5.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.081 ±(99.9%) 3.768 ops/ms [Average]
  (min, avg, max) = (5.873, 6.081, 6.286), stdev = 0.207
  CI (99.9%): [2.314, 9.849] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 4.507 ops/ms
# Warmup Iteration   3: 5.666 ops/ms
Iteration   1: 5.798 ops/ms
Iteration   2: 5.681 ops/ms
Iteration   3: 5.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.820 ±(99.9%) 2.760 ops/ms [Average]
  (min, avg, max) = (5.681, 5.820, 5.981), stdev = 0.151
  CI (99.9%): [3.060, 8.581] (assumes normal distribution)


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
# Warmup Iteration   1: 1.614 ops/ms
# Warmup Iteration   2: 4.207 ops/ms
# Warmup Iteration   3: 5.113 ops/ms
Iteration   1: 5.014 ops/ms
Iteration   2: 5.132 ops/ms
Iteration   3: 4.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.044 ±(99.9%) 1.429 ops/ms [Average]
  (min, avg, max) = (4.985, 5.044, 5.132), stdev = 0.078
  CI (99.9%): [3.614, 6.473] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 18.245 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.642 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.011 ms/op
Iteration   1: 5.367 ±(99.9%) 0.016 ms/op
Iteration   2: 5.405 ±(99.9%) 0.019 ms/op
Iteration   3: 5.505 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.426 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (5.367, 5.426, 5.505), stdev = 0.071
  CI (99.9%): [4.130, 6.721] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 17.987 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.343 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.266 ±(99.9%) 0.009 ms/op
Iteration   1: 5.511 ±(99.9%) 0.009 ms/op
Iteration   2: 5.218 ±(99.9%) 0.014 ms/op
Iteration   3: 5.143 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.291 ±(99.9%) 3.547 ms/op [Average]
  (min, avg, max) = (5.143, 5.291, 5.511), stdev = 0.194
  CI (99.9%): [1.744, 8.837] (assumes normal distribution)


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
# Warmup Iteration   1: 16.593 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.652 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.976 ±(99.9%) 0.006 ms/op
Iteration   1: 5.518 ±(99.9%) 0.017 ms/op
Iteration   2: 5.631 ±(99.9%) 0.007 ms/op
Iteration   3: 5.488 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.546 ±(99.9%) 1.379 ms/op [Average]
  (min, avg, max) = (5.488, 5.546, 5.631), stdev = 0.076
  CI (99.9%): [4.167, 6.925] (assumes normal distribution)


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
# Warmup Iteration   1: 21.424 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 8.043 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.337 ±(99.9%) 0.018 ms/op
Iteration   1: 6.557 ±(99.9%) 0.019 ms/op
Iteration   2: 6.635 ±(99.9%) 0.012 ms/op
Iteration   3: 6.640 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.611 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (6.557, 6.611, 6.640), stdev = 0.046
  CI (99.9%): [5.765, 7.456] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.545 ±(99.9%) 0.386 ms/op
# Warmup Iteration   2: 7.601 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.505 ±(99.9%) 0.035 ms/op
Iteration   1: 5.820 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   7.733 ms/op
                 createUser·p0.95:   8.503 ms/op
                 createUser·p0.99:   11.275 ms/op
                 createUser·p0.999:  29.950 ms/op
                 createUser·p0.9999: 43.222 ms/op
                 createUser·p1.00:   47.579 ms/op

Iteration   2: 5.809 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.474 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   7.324 ms/op
                 createUser·p0.95:   8.143 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  27.525 ms/op
                 createUser·p0.9999: 30.849 ms/op
                 createUser·p1.00:   31.687 ms/op

Iteration   3: 5.578 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.802 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   6.775 ms/op
                 createUser·p0.95:   7.791 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  28.790 ms/op
                 createUser·p0.9999: 32.777 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167437
  mean =      5.733 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 45564 
    [ 5.000, 10.000) = 119294 
    [10.000, 15.000) = 2129 
    [15.000, 20.000) = 190 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 84 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     28.068 ms/op
     p(99.9900) =     40.584 ms/op
     p(99.9990) =     47.579 ms/op
     p(99.9999) =     47.579 ms/op
    p(100.0000) =     47.579 ms/op


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
# Warmup Iteration   1: 16.835 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.232 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.377 ±(99.9%) 0.020 ms/op
Iteration   1: 5.168 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.068 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.422 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  23.536 ms/op
                 existUser·p0.9999: 29.813 ms/op
                 existUser·p1.00:   30.441 ms/op

Iteration   2: 5.290 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.617 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.603 ms/op
                 existUser·p0.95:   7.524 ms/op
                 existUser·p0.99:   9.355 ms/op
                 existUser·p0.999:  18.088 ms/op
                 existUser·p0.9999: 33.683 ms/op
                 existUser·p1.00:   35.717 ms/op

Iteration   3: 5.331 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.152 ms/op
                 existUser·p0.99:   10.280 ms/op
                 existUser·p0.999:  26.409 ms/op
                 existUser·p0.9999: 38.139 ms/op
                 existUser·p1.00:   39.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182314
  mean =      5.262 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 98123 
    [ 5.000,  7.500) = 75856 
    [ 7.500, 10.000) = 6670 
    [10.000, 12.500) = 1048 
    [12.500, 15.000) = 294 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.068 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     36.569 ms/op
     p(99.9990) =     39.356 ms/op
     p(99.9999) =     39.518 ms/op
    p(100.0000) =     39.518 ms/op


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
# Warmup Iteration   1: 17.964 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 7.331 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.619 ±(99.9%) 0.023 ms/op
Iteration   1: 5.682 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.617 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.192 ms/op
                 getUser·p0.99:   11.146 ms/op
                 getUser·p0.999:  23.420 ms/op
                 getUser·p0.9999: 31.027 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   2: 5.673 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.576 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.996 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   11.272 ms/op
                 getUser·p0.999:  26.463 ms/op
                 getUser·p0.9999: 36.438 ms/op
                 getUser·p1.00:   36.504 ms/op

Iteration   3: 5.549 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.486 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.135 ms/op
                 getUser·p0.99:   9.634 ms/op
                 getUser·p0.999:  27.111 ms/op
                 getUser·p0.9999: 30.081 ms/op
                 getUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170307
  mean =      5.634 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 50909 
    [ 5.000,  7.500) = 108880 
    [ 7.500, 10.000) = 7894 
    [10.000, 12.500) = 1709 
    [12.500, 15.000) = 504 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.486 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     24.329 ms/op
     p(99.9900) =     35.441 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 20.179 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 7.659 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.552 ±(99.9%) 0.025 ms/op
Iteration   1: 6.846 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   9.028 ms/op
                 listUser·p0.95:   10.043 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  28.312 ms/op
                 listUser·p0.9999: 31.641 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   2: 6.519 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  31.390 ms/op
                 listUser·p0.9999: 38.089 ms/op
                 listUser·p1.00:   38.928 ms/op

Iteration   3: 6.470 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.412 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.963 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   13.582 ms/op
                 listUser·p0.999:  28.449 ms/op
                 listUser·p0.9999: 34.221 ms/op
                 listUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145177
  mean =      6.608 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 4565 
    [ 5.000,  7.500) = 117678 
    [ 7.500, 10.000) = 17031 
    [10.000, 12.500) = 4349 
    [12.500, 15.000) = 932 
    [15.000, 17.500) = 261 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.087 ms/op
     p(50.0000) =      6.160 ms/op
     p(90.0000) =      8.290 ms/op
     p(95.0000) =      9.634 ms/op
     p(99.0000) =     12.665 ms/op
     p(99.9000) =     29.458 ms/op
     p(99.9900) =     37.154 ms/op
     p(99.9990) =     38.692 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.685 ± 2.604  ops/ms
ClientPb.existUser                       thrpt       3   6.081 ± 3.768  ops/ms
ClientPb.getUser                         thrpt       3   5.820 ± 2.760  ops/ms
ClientPb.listUser                        thrpt       3   5.044 ± 1.429  ops/ms
ClientPb.createUser                       avgt       3   5.426 ± 1.295   ms/op
ClientPb.existUser                        avgt       3   5.291 ± 3.547   ms/op
ClientPb.getUser                          avgt       3   5.546 ± 1.379   ms/op
ClientPb.listUser                         avgt       3   6.611 ± 0.845   ms/op
ClientPb.createUser                     sample  167437   5.733 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.438           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.258           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.994           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.068           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.584           ms/op
ClientPb.createUser:createUser·p1.00    sample          47.579           ms/op
ClientPb.existUser                      sample  182314   5.262 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.068           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.120           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.569           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.518           ms/op
ClientPb.getUser                        sample  170307   5.634 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.333           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.913           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.682           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.329           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.441           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.504           ms/op
ClientPb.listUser                       sample  145177   6.608 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.087           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.290           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.634           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.665           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.458           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.154           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.928           ms/op
