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
# Warmup Iteration   1: 1.716 ops/ms
# Warmup Iteration   2: 3.727 ops/ms
# Warmup Iteration   3: 7.224 ops/ms
Iteration   1: 7.471 ops/ms
Iteration   2: 8.019 ops/ms
Iteration   3: 8.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.893 ±(99.9%) 6.856 ops/ms [Average]
  (min, avg, max) = (7.471, 7.893, 8.190), stdev = 0.376
  CI (99.9%): [1.037, 14.749] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.173 ops/ms
# Warmup Iteration   2: 6.428 ops/ms
# Warmup Iteration   3: 8.524 ops/ms
Iteration   1: 8.238 ops/ms
Iteration   2: 8.620 ops/ms
Iteration   3: 8.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.478 ±(99.9%) 3.815 ops/ms [Average]
  (min, avg, max) = (8.238, 8.478, 8.620), stdev = 0.209
  CI (99.9%): [4.663, 12.292] (assumes normal distribution)


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
# Warmup Iteration   1: 2.187 ops/ms
# Warmup Iteration   2: 6.720 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 8.345 ops/ms
Iteration   2: 8.364 ops/ms
Iteration   3: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.240 ±(99.9%) 3.617 ops/ms [Average]
  (min, avg, max) = (8.011, 8.240, 8.364), stdev = 0.198
  CI (99.9%): [4.623, 11.857] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.044 ops/ms
# Warmup Iteration   2: 5.757 ops/ms
# Warmup Iteration   3: 6.869 ops/ms
Iteration   1: 6.876 ops/ms
Iteration   2: 6.840 ops/ms
Iteration   3: 6.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.895 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (6.840, 6.895, 6.969), stdev = 0.067
  CI (99.9%): [5.678, 8.112] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.917 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.941 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.008 ms/op
Iteration   1: 3.945 ±(99.9%) 0.012 ms/op
Iteration   2: 3.940 ±(99.9%) 0.008 ms/op
Iteration   3: 3.904 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.930 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (3.904, 3.930, 3.945), stdev = 0.022
  CI (99.9%): [3.522, 4.337] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.564 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.657 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.014 ms/op
Iteration   1: 3.741 ±(99.9%) 0.002 ms/op
Iteration   2: 3.676 ±(99.9%) 0.008 ms/op
Iteration   3: 3.630 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.682 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (3.630, 3.682, 3.741), stdev = 0.056
  CI (99.9%): [2.661, 4.703] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.208 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.818 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.006 ms/op
Iteration   1: 4.227 ±(99.9%) 0.008 ms/op
Iteration   2: 4.061 ±(99.9%) 0.008 ms/op
Iteration   3: 4.040 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.109 ±(99.9%) 1.870 ms/op [Average]
  (min, avg, max) = (4.040, 4.109, 4.227), stdev = 0.102
  CI (99.9%): [2.240, 5.979] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.896 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.566 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.787 ±(99.9%) 0.009 ms/op
Iteration   1: 4.779 ±(99.9%) 0.013 ms/op
Iteration   2: 4.483 ±(99.9%) 0.016 ms/op
Iteration   3: 4.518 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.593 ±(99.9%) 2.958 ms/op [Average]
  (min, avg, max) = (4.483, 4.593, 4.779), stdev = 0.162
  CI (99.9%): [1.635, 7.551] (assumes normal distribution)


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
# Warmup Iteration   1: 12.443 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.970 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.017 ms/op
Iteration   1: 3.885 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  24.399 ms/op
                 createUser·p0.9999: 37.618 ms/op
                 createUser·p1.00:   38.339 ms/op

Iteration   2: 4.036 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  24.853 ms/op
                 createUser·p0.9999: 28.183 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 3.999 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.075 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   7.881 ms/op
                 createUser·p0.999:  13.469 ms/op
                 createUser·p0.9999: 30.475 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241545
  mean =      3.972 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 229743 
    [ 5.000,  7.500) = 9331 
    [ 7.500, 10.000) = 1449 
    [10.000, 12.500) = 501 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     38.153 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.954 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.514 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.014 ms/op
Iteration   1: 3.896 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.913 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.913 ms/op
                 existUser·p0.999:  12.448 ms/op
                 existUser·p0.9999: 27.380 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   2: 3.848 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.810 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   7.594 ms/op
                 existUser·p0.999:  13.926 ms/op
                 existUser·p0.9999: 34.910 ms/op
                 existUser·p1.00:   37.356 ms/op

Iteration   3: 3.877 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  26.197 ms/op
                 existUser·p0.9999: 29.270 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247921
  mean =      3.873 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 276 
    [ 2.500,  5.000) = 235956 
    [ 5.000,  7.500) = 8464 
    [ 7.500, 10.000) = 2573 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     13.911 ms/op
     p(99.9900) =     32.473 ms/op
     p(99.9990) =     37.102 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.142 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.015 ms/op
Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.659 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   7.496 ms/op
                 getUser·p0.999:  13.533 ms/op
                 getUser·p0.9999: 25.189 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   2: 3.869 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.800 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.503 ms/op
                 getUser·p0.999:  23.696 ms/op
                 getUser·p0.9999: 33.513 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 4.005 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  11.141 ms/op
                 getUser·p0.9999: 33.294 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245398
  mean =      3.910 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 235794 
    [ 5.000,  7.500) = 7607 
    [ 7.500, 10.000) = 1325 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     32.037 ms/op
     p(99.9990) =     33.983 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 12.985 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.596 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.019 ms/op
Iteration   1: 4.797 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  24.969 ms/op
                 listUser·p0.9999: 26.815 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   2: 4.644 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.818 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 26.452 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 4.590 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   8.388 ms/op
                 listUser·p0.999:  17.681 ms/op
                 listUser·p0.9999: 22.553 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205154
  mean =      4.675 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 180019 
    [ 5.000,  7.500) = 19812 
    [ 7.500, 10.000) = 4226 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 87 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     20.409 ms/op
     p(99.9900) =     26.377 ms/op
     p(99.9990) =     27.556 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.893 ± 6.856  ops/ms
ClientPb.existUser                       thrpt       3   8.478 ± 3.815  ops/ms
ClientPb.getUser                         thrpt       3   8.240 ± 3.617  ops/ms
ClientPb.listUser                        thrpt       3   6.895 ± 1.217  ops/ms
ClientPb.createUser                       avgt       3   3.930 ± 0.408   ms/op
ClientPb.existUser                        avgt       3   3.682 ± 1.021   ms/op
ClientPb.getUser                          avgt       3   4.109 ± 1.870   ms/op
ClientPb.listUser                         avgt       3   4.593 ± 2.958   ms/op
ClientPb.createUser                     sample  241545   3.972 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.464           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.964           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.463           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.183           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.045           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.339           ms/op
ClientPb.existUser                      sample  247921   3.873 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.430           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.963           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.911           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.473           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.356           ms/op
ClientPb.getUser                        sample  245398   3.910 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.626           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.768           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.102           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.533           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.037           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  205154   4.675 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.534           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.667           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.409           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.377           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.886           ms/op
