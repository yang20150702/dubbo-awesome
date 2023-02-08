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
# Warmup Iteration   1: 2.161 ops/ms
# Warmup Iteration   2: 5.102 ops/ms
# Warmup Iteration   3: 8.398 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 9.189 ops/ms
Iteration   3: 9.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.166 ±(99.9%) 1.934 ops/ms [Average]
  (min, avg, max) = (9.050, 9.166, 9.259), stdev = 0.106
  CI (99.9%): [7.232, 11.100] (assumes normal distribution)


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
# Warmup Iteration   1: 2.544 ops/ms
# Warmup Iteration   2: 7.788 ops/ms
# Warmup Iteration   3: 9.517 ops/ms
Iteration   1: 9.270 ops/ms
Iteration   2: 9.889 ops/ms
Iteration   3: 9.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.709 ±(99.9%) 6.976 ops/ms [Average]
  (min, avg, max) = (9.270, 9.709, 9.969), stdev = 0.382
  CI (99.9%): [2.733, 16.685] (assumes normal distribution)


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
# Warmup Iteration   1: 2.733 ops/ms
# Warmup Iteration   2: 8.143 ops/ms
# Warmup Iteration   3: 9.264 ops/ms
Iteration   1: 9.303 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 9.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.421 ±(99.9%) 2.902 ops/ms [Average]
  (min, avg, max) = (9.303, 9.421, 9.602), stdev = 0.159
  CI (99.9%): [6.520, 12.323] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.610 ops/ms
# Warmup Iteration   2: 7.062 ops/ms
# Warmup Iteration   3: 7.866 ops/ms
Iteration   1: 7.906 ops/ms
Iteration   2: 8.114 ops/ms
Iteration   3: 8.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.094 ±(99.9%) 3.258 ops/ms [Average]
  (min, avg, max) = (7.906, 8.094, 8.261), stdev = 0.179
  CI (99.9%): [4.836, 11.351] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.477 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.008 ms/op
Iteration   1: 3.595 ±(99.9%) 0.005 ms/op
Iteration   2: 3.448 ±(99.9%) 0.007 ms/op
Iteration   3: 3.380 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 1.999 ms/op [Average]
  (min, avg, max) = (3.380, 3.474, 3.595), stdev = 0.110
  CI (99.9%): [1.475, 5.473] (assumes normal distribution)


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
# Warmup Iteration   1: 10.044 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.007 ms/op
Iteration   1: 3.465 ±(99.9%) 0.004 ms/op
Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
Iteration   3: 3.331 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.372 ±(99.9%) 1.487 ms/op [Average]
  (min, avg, max) = (3.318, 3.372, 3.465), stdev = 0.082
  CI (99.9%): [1.884, 4.859] (assumes normal distribution)


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
# Warmup Iteration   1: 9.342 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.003 ms/op
Iteration   1: 3.545 ±(99.9%) 0.005 ms/op
Iteration   2: 3.320 ±(99.9%) 0.006 ms/op
Iteration   3: 3.499 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.455 ±(99.9%) 2.170 ms/op [Average]
  (min, avg, max) = (3.320, 3.455, 3.545), stdev = 0.119
  CI (99.9%): [1.285, 5.624] (assumes normal distribution)


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
# Warmup Iteration   1: 10.628 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.457 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.009 ms/op
Iteration   1: 4.014 ±(99.9%) 0.010 ms/op
Iteration   2: 3.993 ±(99.9%) 0.007 ms/op
Iteration   3: 3.815 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.941 ±(99.9%) 1.995 ms/op [Average]
  (min, avg, max) = (3.815, 3.941, 4.014), stdev = 0.109
  CI (99.9%): [1.946, 5.935] (assumes normal distribution)


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
# Warmup Iteration   1: 9.691 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.010 ms/op
Iteration   1: 3.470 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 23.002 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  21.651 ms/op
                 createUser·p0.9999: 25.490 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   3: 3.427 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  23.911 ms/op
                 createUser·p0.9999: 27.635 ms/op
                 createUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280626
  mean =      3.419 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8449 
    [ 2.500,  5.000) = 266169 
    [ 5.000,  7.500) = 5119 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     26.573 ms/op
     p(99.9990) =     28.874 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 8.620 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.010 ms/op
Iteration   1: 3.229 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  9.339 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.254 ms/op
                 existUser·p0.9999: 29.694 ms/op
                 existUser·p1.00:   31.064 ms/op

Iteration   3: 3.374 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  21.420 ms/op
                 existUser·p0.9999: 25.019 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291849
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13532 
    [ 2.500,  5.000) = 273655 
    [ 5.000,  7.500) = 4039 
    [ 7.500, 10.000) = 318 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     10.912 ms/op
     p(99.9900) =     28.863 ms/op
     p(99.9990) =     30.914 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 9.480 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.011 ms/op
Iteration   1: 3.581 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  13.554 ms/op
                 getUser·p0.9999: 22.907 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.545 ms/op
                 getUser·p0.999:  22.184 ms/op
                 getUser·p0.9999: 26.575 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.427 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  19.209 ms/op
                 getUser·p0.9999: 31.282 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276563
  mean =      3.472 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14697 
    [ 2.500,  5.000) = 254675 
    [ 5.000,  7.500) = 6070 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     13.653 ms/op
     p(99.9900) =     29.972 ms/op
     p(99.9990) =     31.800 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 12.967 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.657 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.013 ms/op
Iteration   1: 4.038 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  20.667 ms/op
                 listUser·p0.9999: 22.692 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 4.103 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.819 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 4.024 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 19.513 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236694
  mean =      4.054 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 228021 
    [ 5.000,  7.500) = 6579 
    [ 7.500, 10.000) = 1277 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     15.716 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.140 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.166 ± 1.934  ops/ms
ClientPb.existUser                       thrpt       3   9.709 ± 6.976  ops/ms
ClientPb.getUser                         thrpt       3   9.421 ± 2.902  ops/ms
ClientPb.listUser                        thrpt       3   8.094 ± 3.258  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 1.999   ms/op
ClientPb.existUser                        avgt       3   3.372 ± 1.487   ms/op
ClientPb.getUser                          avgt       3   3.455 ± 2.170   ms/op
ClientPb.listUser                         avgt       3   3.941 ± 1.995   ms/op
ClientPb.createUser                     sample  280626   3.419 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.709           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.573           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.032           ms/op
ClientPb.existUser                      sample  291849   3.287 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.912           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.863           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.064           ms/op
ClientPb.getUser                        sample  276563   3.472 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.944           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.653           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.972           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  236694   4.054 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.337           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.716           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.151           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.265           ms/op
