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
# Warmup Iteration   1: 2.515 ops/ms
# Warmup Iteration   2: 6.197 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 10.117 ops/ms
Iteration   2: 9.811 ops/ms
Iteration   3: 10.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.065 ±(99.9%) 4.254 ops/ms [Average]
  (min, avg, max) = (9.811, 10.065, 10.268), stdev = 0.233
  CI (99.9%): [5.812, 14.319] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ops/ms
# Warmup Iteration   2: 9.367 ops/ms
# Warmup Iteration   3: 10.189 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.420 ±(99.9%) 4.136 ops/ms [Average]
  (min, avg, max) = (10.176, 10.420, 10.624), stdev = 0.227
  CI (99.9%): [6.284, 14.555] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.616 ops/ms
# Warmup Iteration   2: 8.820 ops/ms
# Warmup Iteration   3: 9.575 ops/ms
Iteration   1: 9.804 ops/ms
Iteration   2: 9.650 ops/ms
Iteration   3: 10.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.835 ±(99.9%) 3.706 ops/ms [Average]
  (min, avg, max) = (9.650, 9.835, 10.052), stdev = 0.203
  CI (99.9%): [6.130, 13.541] (assumes normal distribution)


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
# Warmup Iteration   1: 3.393 ops/ms
# Warmup Iteration   2: 7.761 ops/ms
# Warmup Iteration   3: 8.462 ops/ms
Iteration   1: 8.354 ops/ms
Iteration   2: 8.538 ops/ms
Iteration   3: 8.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.496 ±(99.9%) 2.302 ops/ms [Average]
  (min, avg, max) = (8.354, 8.496, 8.595), stdev = 0.126
  CI (99.9%): [6.193, 10.798] (assumes normal distribution)


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
# Warmup Iteration   1: 8.347 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.561 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.006 ms/op
Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
Iteration   3: 3.065 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.136 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (3.065, 3.136, 3.197), stdev = 0.066
  CI (99.9%): [1.926, 4.346] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.996 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.004 ms/op
Iteration   1: 3.077 ±(99.9%) 0.008 ms/op
Iteration   2: 3.113 ±(99.9%) 0.004 ms/op
Iteration   3: 3.158 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.116 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (3.077, 3.116, 3.158), stdev = 0.040
  CI (99.9%): [2.382, 3.850] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.315 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.003 ms/op
Iteration   1: 3.281 ±(99.9%) 0.003 ms/op
Iteration   2: 3.291 ±(99.9%) 0.003 ms/op
Iteration   3: 3.165 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.246 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (3.165, 3.246, 3.291), stdev = 0.070
  CI (99.9%): [1.967, 4.524] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.910 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.006 ms/op
Iteration   1: 3.828 ±(99.9%) 0.005 ms/op
Iteration   2: 3.825 ±(99.9%) 0.005 ms/op
Iteration   3: 3.853 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.835 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.825, 3.835, 3.853), stdev = 0.015
  CI (99.9%): [3.559, 4.112] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.215 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.011 ms/op
Iteration   1: 3.240 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  9.356 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  12.223 ms/op
                 createUser·p0.9999: 27.683 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  16.302 ms/op
                 createUser·p0.9999: 28.616 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297548
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24308 
    [ 2.500,  5.000) = 268420 
    [ 5.000,  7.500) = 4165 
    [ 7.500, 10.000) = 240 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     16.064 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     28.811 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.097 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.974 ms/op
                 existUser·p0.9999: 19.974 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   2: 3.218 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.327 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  17.170 ms/op
                 existUser·p0.9999: 25.141 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  9.257 ms/op
                 existUser·p0.9999: 20.046 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306153
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30099 
    [ 2.500,  5.000) = 270578 
    [ 5.000,  7.500) = 4759 
    [ 7.500, 10.000) = 382 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     12.543 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.455 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.732 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.011 ms/op
Iteration   1: 3.198 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  13.992 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   6.017 ms/op
                 getUser·p0.999:  11.829 ms/op
                 getUser·p0.9999: 22.204 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 28.508 ms/op
                 getUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295650
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10801 
    [ 2.500,  5.000) = 276168 
    [ 5.000,  7.500) = 7709 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     13.932 ms/op
     p(99.9900) =     27.007 ms/op
     p(99.9990) =     29.183 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.702 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.013 ms/op
Iteration   1: 3.769 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 3.748 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   7.157 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 3.725 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.567 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 15.391 ms/op
                 listUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256099
  mean =      3.747 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 249324 
    [ 5.000,  7.500) = 4781 
    [ 7.500, 10.000) = 1293 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     21.088 ms/op
     p(99.9990) =     23.607 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.065 ± 4.254  ops/ms
ClientPb.existUser                       thrpt       3  10.420 ± 4.136  ops/ms
ClientPb.getUser                         thrpt       3   9.835 ± 3.706  ops/ms
ClientPb.listUser                        thrpt       3   8.496 ± 2.302  ops/ms
ClientPb.createUser                       avgt       3   3.136 ± 1.210   ms/op
ClientPb.existUser                        avgt       3   3.116 ± 0.734   ms/op
ClientPb.getUser                          avgt       3   3.246 ± 1.279   ms/op
ClientPb.listUser                         avgt       3   3.835 ± 0.277   ms/op
ClientPb.createUser                     sample  297548   3.225 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.389           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.064           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.394           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.360           ms/op
ClientPb.existUser                      sample  306153   3.135 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.327           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.543           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.757           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.526           ms/op
ClientPb.getUser                        sample  295650   3.245 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.932           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.007           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.376           ms/op
ClientPb.listUser                       sample  256099   3.747 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.567           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.088           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.658           ms/op
