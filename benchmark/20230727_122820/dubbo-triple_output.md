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
# Warmup Iteration   1: 2.565 ops/ms
# Warmup Iteration   2: 6.399 ops/ms
# Warmup Iteration   3: 8.848 ops/ms
Iteration   1: 9.766 ops/ms
Iteration   2: 9.981 ops/ms
Iteration   3: 9.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.808 ±(99.9%) 2.851 ops/ms [Average]
  (min, avg, max) = (9.677, 9.808, 9.981), stdev = 0.156
  CI (99.9%): [6.957, 12.659] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.669 ops/ms
# Warmup Iteration   2: 9.183 ops/ms
# Warmup Iteration   3: 9.843 ops/ms
Iteration   1: 10.006 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.286 ±(99.9%) 4.415 ops/ms [Average]
  (min, avg, max) = (10.006, 10.286, 10.428), stdev = 0.242
  CI (99.9%): [5.871, 14.701] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ops/ms
# Warmup Iteration   2: 8.709 ops/ms
# Warmup Iteration   3: 9.258 ops/ms
Iteration   1: 10.040 ops/ms
Iteration   2: 9.670 ops/ms
Iteration   3: 9.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.877 ±(99.9%) 3.440 ops/ms [Average]
  (min, avg, max) = (9.670, 9.877, 10.040), stdev = 0.189
  CI (99.9%): [6.437, 13.317] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ops/ms
# Warmup Iteration   2: 7.676 ops/ms
# Warmup Iteration   3: 8.228 ops/ms
Iteration   1: 8.523 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.390 ±(99.9%) 3.968 ops/ms [Average]
  (min, avg, max) = (8.139, 8.390, 8.523), stdev = 0.217
  CI (99.9%): [4.422, 12.358] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.626 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.006 ms/op
Iteration   1: 3.233 ±(99.9%) 0.008 ms/op
Iteration   2: 3.126 ±(99.9%) 0.005 ms/op
Iteration   3: 3.060 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.140 ±(99.9%) 1.588 ms/op [Average]
  (min, avg, max) = (3.060, 3.140, 3.233), stdev = 0.087
  CI (99.9%): [1.552, 4.728] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.865 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.008 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
Iteration   3: 3.142 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.144 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.099, 3.144, 3.192), stdev = 0.046
  CI (99.9%): [2.297, 3.992] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.566 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.005 ms/op
Iteration   1: 3.200 ±(99.9%) 0.004 ms/op
Iteration   2: 3.257 ±(99.9%) 0.003 ms/op
Iteration   3: 3.154 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.203 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.154, 3.203, 3.257), stdev = 0.052
  CI (99.9%): [2.263, 4.144] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.006 ms/op
Iteration   1: 3.820 ±(99.9%) 0.006 ms/op
Iteration   2: 3.775 ±(99.9%) 0.008 ms/op
Iteration   3: 3.793 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.796 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (3.775, 3.796, 3.820), stdev = 0.023
  CI (99.9%): [3.386, 4.207] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.047 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.010 ms/op
Iteration   1: 3.367 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  17.762 ms/op
                 createUser·p0.9999: 23.004 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  9.103 ms/op
                 createUser·p0.9999: 22.710 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  14.361 ms/op
                 createUser·p0.9999: 25.751 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298119
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13195 
    [ 2.500,  5.000) = 278924 
    [ 5.000,  7.500) = 5133 
    [ 7.500, 10.000) = 390 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.381 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     27.070 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 7.738 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  12.195 ms/op
                 existUser·p0.9999: 19.652 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  8.901 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.640 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.322 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.397 ms/op
                 existUser·p0.9999: 19.661 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311766
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15191 
    [ 2.500,  5.000) = 291580 
    [ 5.000,  7.500) = 4449 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     10.407 ms/op
     p(99.9900) =     21.752 ms/op
     p(99.9990) =     23.458 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 8.779 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.031 ms/op
                 getUser·p0.999:  14.664 ms/op
                 getUser·p0.9999: 20.443 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.326 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  10.827 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304903
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13641 
    [ 2.500,  5.000) = 285176 
    [ 5.000,  7.500) = 5486 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     10.831 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     22.281 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 9.275 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.011 ms/op
Iteration   1: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  15.969 ms/op
                 listUser·p0.9999: 22.489 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 3.755 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.416 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   3: 3.814 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 15.147 ms/op
                 listUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251383
  mean =      3.817 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 243653 
    [ 5.000,  7.500) = 5815 
    [ 7.500, 10.000) = 1137 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     20.527 ms/op
     p(99.9990) =     23.166 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.808 ± 2.851  ops/ms
ClientPb.existUser                       thrpt       3  10.286 ± 4.415  ops/ms
ClientPb.getUser                         thrpt       3   9.877 ± 3.440  ops/ms
ClientPb.listUser                        thrpt       3   8.390 ± 3.968  ops/ms
ClientPb.createUser                       avgt       3   3.140 ± 1.588   ms/op
ClientPb.existUser                        avgt       3   3.144 ± 0.847   ms/op
ClientPb.getUser                          avgt       3   3.203 ± 0.941   ms/op
ClientPb.listUser                         avgt       3   3.796 ± 0.411   ms/op
ClientPb.createUser                     sample  298119   3.219 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.029           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.381           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.347           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.394           ms/op
ClientPb.existUser                      sample  311766   3.078 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.186           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.407           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.752           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.658           ms/op
ClientPb.getUser                        sample  304903   3.149 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.587           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.831           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.873           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.413           ms/op
ClientPb.listUser                       sample  251383   3.817 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.313           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.057           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
