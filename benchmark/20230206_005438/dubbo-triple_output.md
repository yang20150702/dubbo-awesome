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
# Warmup Iteration   1: 2.254 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.303 ops/ms
Iteration   2: 9.400 ops/ms
Iteration   3: 9.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.308 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (9.222, 9.308, 9.400), stdev = 0.089
  CI (99.9%): [7.686, 10.931] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.184 ops/ms
# Warmup Iteration   2: 8.977 ops/ms
# Warmup Iteration   3: 9.476 ops/ms
Iteration   1: 9.735 ops/ms
Iteration   2: 9.569 ops/ms
Iteration   3: 9.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.751 ±(99.9%) 3.473 ops/ms [Average]
  (min, avg, max) = (9.569, 9.751, 9.949), stdev = 0.190
  CI (99.9%): [6.278, 13.224] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 8.349 ops/ms
# Warmup Iteration   3: 9.239 ops/ms
Iteration   1: 9.328 ops/ms
Iteration   2: 9.363 ops/ms
Iteration   3: 9.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.298 ±(99.9%) 1.525 ops/ms [Average]
  (min, avg, max) = (9.204, 9.298, 9.363), stdev = 0.084
  CI (99.9%): [7.773, 10.823] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ops/ms
# Warmup Iteration   2: 7.114 ops/ms
# Warmup Iteration   3: 8.106 ops/ms
Iteration   1: 8.185 ops/ms
Iteration   2: 7.917 ops/ms
Iteration   3: 7.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.005 ±(99.9%) 2.853 ops/ms [Average]
  (min, avg, max) = (7.912, 8.005, 8.185), stdev = 0.156
  CI (99.9%): [5.152, 10.858] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.200 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.007 ms/op
Iteration   1: 3.489 ±(99.9%) 0.009 ms/op
Iteration   2: 3.426 ±(99.9%) 0.010 ms/op
Iteration   3: 3.269 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.395 ±(99.9%) 2.070 ms/op [Average]
  (min, avg, max) = (3.269, 3.395, 3.489), stdev = 0.113
  CI (99.9%): [1.325, 5.465] (assumes normal distribution)


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
# Warmup Iteration   1: 8.295 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.007 ms/op
Iteration   1: 3.230 ±(99.9%) 0.007 ms/op
Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
Iteration   3: 3.265 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.240 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.226, 3.240, 3.265), stdev = 0.021
  CI (99.9%): [2.856, 3.625] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.858 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.004 ms/op
Iteration   1: 3.457 ±(99.9%) 0.008 ms/op
Iteration   2: 3.423 ±(99.9%) 0.008 ms/op
Iteration   3: 3.370 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.416 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (3.370, 3.416, 3.457), stdev = 0.044
  CI (99.9%): [2.618, 4.215] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.525 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.009 ms/op
Iteration   1: 3.940 ±(99.9%) 0.010 ms/op
Iteration   2: 3.999 ±(99.9%) 0.013 ms/op
Iteration   3: 3.895 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.944 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (3.895, 3.944, 3.999), stdev = 0.052
  CI (99.9%): [2.994, 4.895] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.783 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
Iteration   1: 3.413 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  20.452 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  22.773 ms/op
                 createUser·p0.9999: 29.275 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 3.339 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  15.712 ms/op
                 createUser·p0.9999: 25.638 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282656
  mean =      3.397 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12905 
    [ 2.500,  5.000) = 263483 
    [ 5.000,  7.500) = 5179 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     29.766 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.724 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.235 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  7.480 ms/op
                 existUser·p0.9999: 23.370 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  10.959 ms/op
                 existUser·p0.9999: 24.386 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.296 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  16.474 ms/op
                 existUser·p0.9999: 24.659 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293857
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8735 
    [ 2.500,  5.000) = 280964 
    [ 5.000,  7.500) = 3216 
    [ 7.500, 10.000) = 502 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 139 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     12.185 ms/op
     p(99.9900) =     24.367 ms/op
     p(99.9990) =     25.159 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 8.712 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.013 ms/op
Iteration   1: 3.586 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  14.156 ms/op
                 getUser·p0.9999: 23.761 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 3.609 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   7.570 ms/op
                 getUser·p0.999:  22.768 ms/op
                 getUser·p0.9999: 28.747 ms/op
                 getUser·p1.00:   30.114 ms/op

Iteration   3: 3.794 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  20.538 ms/op
                 getUser·p0.9999: 29.955 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262148
  mean =      3.661 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8087 
    [ 2.500,  5.000) = 234388 
    [ 5.000,  7.500) = 17438 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     19.623 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     30.950 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 10.420 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.532 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.012 ms/op
Iteration   1: 4.048 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.751 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  17.558 ms/op
                 listUser·p0.9999: 22.151 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  17.279 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   32.965 ms/op

Iteration   3: 3.946 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 16.726 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239869
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 231049 
    [ 5.000,  7.500) = 6292 
    [ 7.500, 10.000) = 1477 
    [10.000, 12.500) = 392 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.751 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.555 ms/op
     p(99.9000) =     16.208 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     24.059 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.308 ± 1.622  ops/ms
ClientPb.existUser                       thrpt       3   9.751 ± 3.473  ops/ms
ClientPb.getUser                         thrpt       3   9.298 ± 1.525  ops/ms
ClientPb.listUser                        thrpt       3   8.005 ± 2.853  ops/ms
ClientPb.createUser                       avgt       3   3.395 ± 2.070   ms/op
ClientPb.existUser                        avgt       3   3.240 ± 0.385   ms/op
ClientPb.getUser                          avgt       3   3.416 ± 0.799   ms/op
ClientPb.listUser                         avgt       3   3.944 ± 0.950   ms/op
ClientPb.createUser                     sample  282656   3.397 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.186           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.843           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.886           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.048           ms/op
ClientPb.existUser                      sample  293857   3.263 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.319           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.185           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.367           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.985           ms/op
ClientPb.getUser                        sample  262148   3.661 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.307           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.623           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.393           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.293           ms/op
ClientPb.listUser                       sample  239869   3.998 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.751           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.555           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.660           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.965           ms/op
