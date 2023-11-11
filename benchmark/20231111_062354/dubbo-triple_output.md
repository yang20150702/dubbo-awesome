# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.322 ops/ms
# Warmup Iteration   2: 6.525 ops/ms
# Warmup Iteration   3: 8.796 ops/ms
Iteration   1: 9.349 ops/ms
Iteration   2: 9.523 ops/ms
Iteration   3: 9.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.400 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (9.328, 9.400, 9.523), stdev = 0.107
  CI (99.9%): [7.452, 11.348] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.367 ops/ms
# Warmup Iteration   2: 8.777 ops/ms
# Warmup Iteration   3: 9.654 ops/ms
Iteration   1: 9.690 ops/ms
Iteration   2: 9.665 ops/ms
Iteration   3: 9.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.706 ±(99.9%) 0.927 ops/ms [Average]
  (min, avg, max) = (9.665, 9.706, 9.763), stdev = 0.051
  CI (99.9%): [8.779, 10.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.349 ops/ms
# Warmup Iteration   2: 8.969 ops/ms
# Warmup Iteration   3: 9.083 ops/ms
Iteration   1: 9.533 ops/ms
Iteration   2: 9.104 ops/ms
Iteration   3: 9.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.364 ±(99.9%) 4.164 ops/ms [Average]
  (min, avg, max) = (9.104, 9.364, 9.533), stdev = 0.228
  CI (99.9%): [5.199, 13.528] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.748 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 7.846 ops/ms
Iteration   3: 7.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.909 ±(99.9%) 1.382 ops/ms [Average]
  (min, avg, max) = (7.846, 7.909, 7.993), stdev = 0.076
  CI (99.9%): [6.527, 9.291] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.106 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.002 ms/op
Iteration   1: 3.512 ±(99.9%) 0.005 ms/op
Iteration   2: 3.420 ±(99.9%) 0.003 ms/op
Iteration   3: 3.428 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.453 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.420, 3.453, 3.512), stdev = 0.051
  CI (99.9%): [2.525, 4.382] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.104 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.004 ms/op
Iteration   1: 3.297 ±(99.9%) 0.003 ms/op
Iteration   2: 3.329 ±(99.9%) 0.004 ms/op
Iteration   3: 3.287 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.304 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.287, 3.304, 3.329), stdev = 0.022
  CI (99.9%): [2.912, 3.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.091 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.004 ms/op
Iteration   1: 3.569 ±(99.9%) 0.002 ms/op
Iteration   2: 3.426 ±(99.9%) 0.004 ms/op
Iteration   3: 3.470 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.489 ±(99.9%) 1.339 ms/op [Average]
  (min, avg, max) = (3.426, 3.489, 3.569), stdev = 0.073
  CI (99.9%): [2.150, 4.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.240 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.007 ms/op
Iteration   1: 4.009 ±(99.9%) 0.009 ms/op
Iteration   2: 4.020 ±(99.9%) 0.006 ms/op
Iteration   3: 4.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.038 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (4.009, 4.038, 4.084), stdev = 0.041
  CI (99.9%): [3.298, 4.777] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.516 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.009 ms/op
Iteration   1: 3.420 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.522 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.495 ms/op
                 createUser·p0.999:  21.407 ms/op
                 createUser·p0.9999: 23.811 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.285 ms/op
                 createUser·p0.999:  16.041 ms/op
                 createUser·p0.9999: 24.551 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275494
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7209 
    [ 2.500,  5.000) = 262881 
    [ 5.000,  7.500) = 4008 
    [ 7.500, 10.000) = 671 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     23.586 ms/op
     p(99.9990) =     24.920 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.174 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.008 ms/op
Iteration   1: 3.259 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  8.011 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 3.339 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.623 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  20.520 ms/op
                 existUser·p0.9999: 26.294 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.390 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  17.666 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288259
  mean =      3.329 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10503 
    [ 2.500,  5.000) = 273085 
    [ 5.000,  7.500) = 3276 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     15.397 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.784 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.010 ms/op
Iteration   1: 3.455 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  20.328 ms/op
                 getUser·p0.9999: 23.630 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.497 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  21.660 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 3.486 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.349 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.914 ms/op
                 getUser·p0.999:  17.934 ms/op
                 getUser·p0.9999: 26.398 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275823
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4124 
    [ 2.500,  5.000) = 263965 
    [ 5.000,  7.500) = 6415 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 152 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     19.699 ms/op
     p(99.9900) =     24.786 ms/op
     p(99.9990) =     26.853 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.389 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.012 ms/op
Iteration   1: 4.190 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  18.461 ms/op
                 listUser·p0.9999: 22.458 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 4.100 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 4.113 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.471 ms/op
                 listUser·p0.9999: 16.281 ms/op
                 listUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232087
  mean =      4.134 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 223390 
    [ 5.000,  7.500) = 6506 
    [ 7.500, 10.000) = 1255 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 388 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     21.194 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.400 ± 1.948  ops/ms
ClientPb.existUser                       thrpt       3   9.706 ± 0.927  ops/ms
ClientPb.getUser                         thrpt       3   9.364 ± 4.164  ops/ms
ClientPb.listUser                        thrpt       3   7.909 ± 1.382  ops/ms
ClientPb.createUser                       avgt       3   3.453 ± 0.929   ms/op
ClientPb.existUser                        avgt       3   3.304 ± 0.393   ms/op
ClientPb.getUser                          avgt       3   3.489 ± 1.339   ms/op
ClientPb.listUser                         avgt       3   4.038 ± 0.740   ms/op
ClientPb.createUser                     sample  275494   3.482 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.586           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.264           ms/op
ClientPb.existUser                      sample  288259   3.329 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.061           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.397           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.331           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.378           ms/op
ClientPb.getUser                        sample  275823   3.479 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.349           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.699           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.786           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.903           ms/op
ClientPb.listUser                       sample  232087   4.134 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.438           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.335           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.194           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.872           ms/op
