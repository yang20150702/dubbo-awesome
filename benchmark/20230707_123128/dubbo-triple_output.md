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
# Warmup Iteration   1: 1.508 ops/ms
# Warmup Iteration   2: 3.400 ops/ms
# Warmup Iteration   3: 6.490 ops/ms
Iteration   1: 7.794 ops/ms
Iteration   2: 8.268 ops/ms
Iteration   3: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.162 ±(99.9%) 5.998 ops/ms [Average]
  (min, avg, max) = (7.794, 8.162, 8.425), stdev = 0.329
  CI (99.9%): [2.164, 14.160] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.294 ops/ms
# Warmup Iteration   2: 7.353 ops/ms
# Warmup Iteration   3: 8.155 ops/ms
Iteration   1: 8.367 ops/ms
Iteration   2: 8.656 ops/ms
Iteration   3: 8.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.563 ±(99.9%) 3.101 ops/ms [Average]
  (min, avg, max) = (8.367, 8.563, 8.666), stdev = 0.170
  CI (99.9%): [5.462, 11.664] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.368 ops/ms
# Warmup Iteration   2: 7.214 ops/ms
# Warmup Iteration   3: 7.822 ops/ms
Iteration   1: 8.332 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.223 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (8.161, 8.223, 8.332), stdev = 0.094
  CI (99.9%): [6.501, 9.946] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.150 ops/ms
# Warmup Iteration   2: 5.283 ops/ms
# Warmup Iteration   3: 7.144 ops/ms
Iteration   1: 6.972 ops/ms
Iteration   2: 7.154 ops/ms
Iteration   3: 6.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.953 ±(99.9%) 3.847 ops/ms [Average]
  (min, avg, max) = (6.734, 6.953, 7.154), stdev = 0.211
  CI (99.9%): [3.106, 10.800] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.551 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.712 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.004 ms/op
Iteration   1: 3.955 ±(99.9%) 0.008 ms/op
Iteration   2: 3.881 ±(99.9%) 0.008 ms/op
Iteration   3: 3.975 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.937 ±(99.9%) 0.902 ms/op [Average]
  (min, avg, max) = (3.881, 3.937, 3.975), stdev = 0.049
  CI (99.9%): [3.035, 4.839] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.652 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.007 ms/op
Iteration   1: 3.736 ±(99.9%) 0.003 ms/op
Iteration   2: 3.733 ±(99.9%) 0.005 ms/op
Iteration   3: 3.844 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.771 ±(99.9%) 1.144 ms/op [Average]
  (min, avg, max) = (3.733, 3.771, 3.844), stdev = 0.063
  CI (99.9%): [2.627, 4.915] (assumes normal distribution)


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
# Warmup Iteration   1: 11.373 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.006 ms/op
Iteration   1: 3.993 ±(99.9%) 0.006 ms/op
Iteration   2: 4.004 ±(99.9%) 0.003 ms/op
Iteration   3: 3.869 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.955 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (3.869, 3.955, 4.004), stdev = 0.075
  CI (99.9%): [2.580, 5.330] (assumes normal distribution)


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
# Warmup Iteration   1: 13.060 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.920 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.678 ±(99.9%) 0.010 ms/op
Iteration   1: 4.634 ±(99.9%) 0.013 ms/op
Iteration   2: 4.517 ±(99.9%) 0.015 ms/op
Iteration   3: 4.514 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.555 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (4.514, 4.555, 4.634), stdev = 0.068
  CI (99.9%): [3.308, 5.802] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 12.950 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 5.448 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.018 ms/op
Iteration   1: 3.938 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  24.337 ms/op
                 createUser·p0.9999: 27.165 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.869 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  25.029 ms/op
                 createUser·p0.9999: 31.103 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   3: 3.703 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  12.082 ms/op
                 createUser·p0.9999: 35.962 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 250303
  mean =      3.834 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 357 
    [ 2.500,  5.000) = 239282 
    [ 5.000,  7.500) = 9373 
    [ 7.500, 10.000) = 786 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     23.966 ms/op
     p(99.9900) =     34.667 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 10.264 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.013 ms/op
Iteration   1: 3.821 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  22.354 ms/op
                 existUser·p0.9999: 25.809 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   2: 3.891 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.030 ms/op
                 existUser·p0.99:   7.668 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 27.813 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.776 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.386 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  27.303 ms/op
                 existUser·p0.9999: 43.031 ms/op
                 existUser·p1.00:   43.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250720
  mean =      3.829 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 240469 
    [ 5.000, 10.000) = 9761 
    [10.000, 15.000) = 234 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 62 
    [25.000, 30.000) = 134 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.158 ms/op
     p(99.9000) =     21.734 ms/op
     p(99.9900) =     41.409 ms/op
     p(99.9990) =     43.580 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


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
# Warmup Iteration   1: 11.550 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.015 ms/op
Iteration   1: 4.096 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.359 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  24.537 ms/op
                 getUser·p0.9999: 51.184 ms/op
                 getUser·p1.00:   51.642 ms/op

Iteration   2: 4.107 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  14.108 ms/op
                 getUser·p0.9999: 30.252 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   3: 3.968 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  27.717 ms/op
                 getUser·p0.9999: 30.243 ms/op
                 getUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236668
  mean =      4.056 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 218996 
    [ 5.000, 10.000) = 17203 
    [10.000, 15.000) = 149 
    [15.000, 20.000) = 64 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 155 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     50.528 ms/op
     p(99.9990) =     51.398 ms/op
     p(99.9999) =     51.642 ms/op
    p(100.0000) =     51.642 ms/op


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
# Warmup Iteration   1: 13.626 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.673 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.751 ±(99.9%) 0.017 ms/op
Iteration   1: 4.601 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.972 ms/op
                 listUser·p0.999:  23.672 ms/op
                 listUser·p0.9999: 28.152 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   2: 4.513 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 21.296 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 4.588 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.789 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  17.050 ms/op
                 listUser·p0.9999: 20.974 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 210093
  mean =      4.567 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 191054 
    [ 5.000,  7.500) = 16145 
    [ 7.500, 10.000) = 2019 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      2.183 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     18.970 ms/op
     p(99.9900) =     26.935 ms/op
     p(99.9990) =     28.469 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.162 ± 5.998  ops/ms
ClientPb.existUser                       thrpt       3   8.563 ± 3.101  ops/ms
ClientPb.getUser                         thrpt       3   8.223 ± 1.722  ops/ms
ClientPb.listUser                        thrpt       3   6.953 ± 3.847  ops/ms
ClientPb.createUser                       avgt       3   3.937 ± 0.902   ms/op
ClientPb.existUser                        avgt       3   3.771 ± 1.144   ms/op
ClientPb.getUser                          avgt       3   3.955 ± 1.375   ms/op
ClientPb.listUser                         avgt       3   4.555 ± 1.247   ms/op
ClientPb.createUser                     sample  250303   3.834 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.210           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.792           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.447           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.966           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.667           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.766           ms/op
ClientPb.existUser                      sample  250720   3.829 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.158           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.734           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.409           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.778           ms/op
ClientPb.getUser                        sample  236668   4.056 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.354           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.576           ms/op
ClientPb.getUser:getUser·p0.9999        sample          50.528           ms/op
ClientPb.getUser:getUser·p1.00          sample          51.642           ms/op
ClientPb.listUser                       sample  210093   4.567 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.183           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.964           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.292           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.020           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.970           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.935           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.541           ms/op
