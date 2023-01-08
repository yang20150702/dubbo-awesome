# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.426 ops/ms
# Warmup Iteration   2: 6.716 ops/ms
# Warmup Iteration   3: 9.623 ops/ms
Iteration   1: 10.172 ops/ms
Iteration   2: 10.197 ops/ms
Iteration   3: 9.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.024 ±(99.9%) 5.085 ops/ms [Average]
  (min, avg, max) = (9.702, 10.024, 10.197), stdev = 0.279
  CI (99.9%): [4.939, 15.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.362 ops/ms
# Warmup Iteration   2: 9.280 ops/ms
# Warmup Iteration   3: 9.658 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 10.224 ops/ms
Iteration   3: 10.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.590 ±(99.9%) 6.882 ops/ms [Average]
  (min, avg, max) = (10.224, 10.590, 10.978), stdev = 0.377
  CI (99.9%): [3.708, 17.472] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ops/ms
# Warmup Iteration   2: 9.253 ops/ms
# Warmup Iteration   3: 9.818 ops/ms
Iteration   1: 10.086 ops/ms
Iteration   2: 9.929 ops/ms
Iteration   3: 9.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.994 ±(99.9%) 1.496 ops/ms [Average]
  (min, avg, max) = (9.929, 9.994, 10.086), stdev = 0.082
  CI (99.9%): [8.497, 11.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 8.146 ops/ms
# Warmup Iteration   3: 8.495 ops/ms
Iteration   1: 8.813 ops/ms
Iteration   2: 8.637 ops/ms
Iteration   3: 8.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.658 ±(99.9%) 2.640 ops/ms [Average]
  (min, avg, max) = (8.525, 8.658, 8.813), stdev = 0.145
  CI (99.9%): [6.018, 11.298] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.899 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.002 ms/op
Iteration   1: 3.196 ±(99.9%) 0.004 ms/op
Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
Iteration   3: 3.109 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.118 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.049, 3.118, 3.196), stdev = 0.074
  CI (99.9%): [1.775, 4.461] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.832 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.005 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
Iteration   3: 3.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.077 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (3.061, 3.077, 3.103), stdev = 0.023
  CI (99.9%): [2.661, 3.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.363 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.002 ms/op
Iteration   1: 3.310 ±(99.9%) 0.003 ms/op
Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
Iteration   3: 3.099 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.174 ±(99.9%) 2.144 ms/op [Average]
  (min, avg, max) = (3.099, 3.174, 3.310), stdev = 0.117
  CI (99.9%): [1.031, 5.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.988 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.008 ms/op
Iteration   1: 3.702 ±(99.9%) 0.009 ms/op
Iteration   2: 3.710 ±(99.9%) 0.005 ms/op
Iteration   3: 3.710 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.707 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (3.702, 3.707, 3.710), stdev = 0.004
  CI (99.9%): [3.627, 3.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.959 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
Iteration   1: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  16.320 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  16.531 ms/op
                 createUser·p0.9999: 22.502 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  15.188 ms/op
                 createUser·p0.9999: 17.855 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306939
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18427 
    [ 2.500,  5.000) = 283850 
    [ 5.000,  7.500) = 3744 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     15.679 ms/op
     p(99.9900) =     21.473 ms/op
     p(99.9990) =     22.673 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.739 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 3.139 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.071 ms/op
                 existUser·p0.999:  12.812 ms/op
                 existUser·p0.9999: 20.042 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  10.253 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   4.836 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 20.525 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309453
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22789 
    [ 2.500,  5.000) = 282036 
    [ 5.000,  7.500) = 3864 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     20.973 ms/op
     p(99.9990) =     22.300 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.145 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
Iteration   1: 3.353 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  16.897 ms/op
                 getUser·p0.9999: 26.116 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 23.099 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 3.099 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  16.493 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299232
  mean =      3.207 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14656 
    [ 2.500,  5.000) = 276951 
    [ 5.000,  7.500) = 6713 
    [ 7.500, 10.000) = 541 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     16.274 ms/op
     p(99.9900) =     24.382 ms/op
     p(99.9990) =     26.609 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.418 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.011 ms/op
Iteration   1: 3.790 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  17.421 ms/op
                 listUser·p0.9999: 18.893 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.678 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.633 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   5.939 ms/op
                 listUser·p0.999:  12.386 ms/op
                 listUser·p0.9999: 15.303 ms/op
                 listUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258424
  mean =      3.711 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 251362 
    [ 5.000,  7.500) = 4928 
    [ 7.500, 10.000) = 1357 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.024 ± 5.085  ops/ms
ClientPb.existUser                       thrpt       3  10.590 ± 6.882  ops/ms
ClientPb.getUser                         thrpt       3   9.994 ± 1.496  ops/ms
ClientPb.listUser                        thrpt       3   8.658 ± 2.640  ops/ms
ClientPb.createUser                       avgt       3   3.118 ± 1.343   ms/op
ClientPb.existUser                        avgt       3   3.077 ± 0.417   ms/op
ClientPb.getUser                          avgt       3   3.174 ± 2.144   ms/op
ClientPb.listUser                         avgt       3   3.707 ± 0.081   ms/op
ClientPb.createUser                     sample  306939   3.125 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.679           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.473           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.839           ms/op
ClientPb.existUser                      sample  309453   3.101 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.611           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.173           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.973           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.577           ms/op
ClientPb.getUser                        sample  299232   3.207 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.659           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.576           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.274           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.382           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.837           ms/op
ClientPb.listUser                       sample  258424   3.711 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.276           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.559           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.366           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.775           ms/op
