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
# Warmup Iteration   1: 2.636 ops/ms
# Warmup Iteration   2: 6.310 ops/ms
# Warmup Iteration   3: 9.152 ops/ms
Iteration   1: 9.744 ops/ms
Iteration   2: 10.048 ops/ms
Iteration   3: 9.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.846 ±(99.9%) 3.200 ops/ms [Average]
  (min, avg, max) = (9.744, 9.846, 10.048), stdev = 0.175
  CI (99.9%): [6.646, 13.045] (assumes normal distribution)


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
# Warmup Iteration   1: 3.340 ops/ms
# Warmup Iteration   2: 9.189 ops/ms
# Warmup Iteration   3: 10.032 ops/ms
Iteration   1: 10.160 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 9.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.111 ±(99.9%) 2.265 ops/ms [Average]
  (min, avg, max) = (9.970, 10.111, 10.204), stdev = 0.124
  CI (99.9%): [7.846, 12.376] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.508 ops/ms
# Warmup Iteration   2: 9.358 ops/ms
# Warmup Iteration   3: 9.973 ops/ms
Iteration   1: 10.334 ops/ms
Iteration   2: 10.344 ops/ms
Iteration   3: 9.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.178 ±(99.9%) 5.101 ops/ms [Average]
  (min, avg, max) = (9.855, 10.178, 10.344), stdev = 0.280
  CI (99.9%): [5.077, 15.278] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.197 ops/ms
# Warmup Iteration   2: 7.486 ops/ms
# Warmup Iteration   3: 8.200 ops/ms
Iteration   1: 8.540 ops/ms
Iteration   2: 8.484 ops/ms
Iteration   3: 8.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.425 ±(99.9%) 2.811 ops/ms [Average]
  (min, avg, max) = (8.250, 8.425, 8.540), stdev = 0.154
  CI (99.9%): [5.613, 11.236] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.921 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.007 ms/op
Iteration   1: 3.328 ±(99.9%) 0.007 ms/op
Iteration   2: 3.223 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.229 ±(99.9%) 1.739 ms/op [Average]
  (min, avg, max) = (3.137, 3.229, 3.328), stdev = 0.095
  CI (99.9%): [1.490, 4.968] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.859 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.074 ±(99.9%) 0.004 ms/op
Iteration   3: 3.094 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.067 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.032, 3.067, 3.094), stdev = 0.032
  CI (99.9%): [2.488, 3.645] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.952 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.003 ms/op
Iteration   1: 3.277 ±(99.9%) 0.003 ms/op
Iteration   2: 3.184 ±(99.9%) 0.007 ms/op
Iteration   3: 3.157 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.206 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.157, 3.206, 3.277), stdev = 0.063
  CI (99.9%): [2.053, 4.359] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.112 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.007 ms/op
Iteration   1: 3.728 ±(99.9%) 0.009 ms/op
Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
Iteration   3: 3.691 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.711 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.691, 3.711, 3.728), stdev = 0.019
  CI (99.9%): [3.373, 4.049] (assumes normal distribution)


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
# Warmup Iteration   1: 7.971 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
Iteration   1: 3.361 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  17.337 ms/op
                 createUser·p0.9999: 22.748 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.777 ms/op
                 createUser·p0.999:  19.858 ms/op
                 createUser·p0.9999: 22.063 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  10.299 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293569
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16084 
    [ 2.500,  5.000) = 271820 
    [ 5.000,  7.500) = 4662 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     15.801 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     23.465 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 7.037 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.009 ms/op
Iteration   1: 3.047 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  11.212 ms/op
                 existUser·p0.9999: 23.773 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  10.583 ms/op
                 existUser·p0.9999: 21.427 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307703
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27471 
    [ 2.500,  5.000) = 275148 
    [ 5.000,  7.500) = 4451 
    [ 7.500, 10.000) = 287 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 7.517 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
Iteration   1: 3.364 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  18.135 ms/op
                 getUser·p0.9999: 21.299 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  8.434 ms/op
                 getUser·p0.9999: 26.867 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  14.681 ms/op
                 getUser·p0.9999: 21.647 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292525
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13487 
    [ 2.500,  5.000) = 269317 
    [ 5.000,  7.500) = 8688 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     15.170 ms/op
     p(99.9900) =     26.304 ms/op
     p(99.9990) =     27.568 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 8.827 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.011 ms/op
Iteration   1: 3.789 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.227 ms/op
                 listUser·p0.9999: 22.956 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 3.758 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.907 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 15.433 ms/op
                 listUser·p1.00:   16.581 ms/op

Iteration   3: 3.801 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.006 ms/op
                 listUser·p0.999:  15.645 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253569
  mean =      3.783 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 246048 
    [ 5.000,  7.500) = 5684 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.859 ms/op
     p(99.9000) =     14.638 ms/op
     p(99.9900) =     21.484 ms/op
     p(99.9990) =     23.477 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.846 ± 3.200  ops/ms
ClientPb.existUser                       thrpt       3  10.111 ± 2.265  ops/ms
ClientPb.getUser                         thrpt       3  10.178 ± 5.101  ops/ms
ClientPb.listUser                        thrpt       3   8.425 ± 2.811  ops/ms
ClientPb.createUser                       avgt       3   3.229 ± 1.739   ms/op
ClientPb.existUser                        avgt       3   3.067 ± 0.578   ms/op
ClientPb.getUser                          avgt       3   3.206 ± 1.153   ms/op
ClientPb.listUser                         avgt       3   3.711 ± 0.338   ms/op
ClientPb.createUser                     sample  293569   3.274 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.029           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.801           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.987           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.543           ms/op
ClientPb.existUser                      sample  307703   3.118 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.697           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.938           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.002           ms/op
ClientPb.getUser                        sample  292525   3.282 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.739           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.170           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  253569   3.783 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.101           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.859           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.638           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.484           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.658           ms/op
