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
# Warmup Iteration   1: 2.528 ops/ms
# Warmup Iteration   2: 5.777 ops/ms
# Warmup Iteration   3: 8.935 ops/ms
Iteration   1: 10.183 ops/ms
Iteration   2: 9.703 ops/ms
Iteration   3: 10.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.029 ±(99.9%) 5.147 ops/ms [Average]
  (min, avg, max) = (9.703, 10.029, 10.200), stdev = 0.282
  CI (99.9%): [4.882, 15.175] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ops/ms
# Warmup Iteration   2: 9.439 ops/ms
# Warmup Iteration   3: 9.915 ops/ms
Iteration   1: 10.543 ops/ms
Iteration   2: 10.343 ops/ms
Iteration   3: 10.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.536 ±(99.9%) 3.471 ops/ms [Average]
  (min, avg, max) = (10.343, 10.536, 10.723), stdev = 0.190
  CI (99.9%): [7.066, 14.007] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ops/ms
# Warmup Iteration   2: 9.412 ops/ms
# Warmup Iteration   3: 9.935 ops/ms
Iteration   1: 10.144 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.263 ±(99.9%) 1.924 ops/ms [Average]
  (min, avg, max) = (10.144, 10.263, 10.345), stdev = 0.105
  CI (99.9%): [8.339, 12.187] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.942 ops/ms
# Warmup Iteration   2: 7.948 ops/ms
# Warmup Iteration   3: 8.441 ops/ms
Iteration   1: 8.456 ops/ms
Iteration   2: 8.578 ops/ms
Iteration   3: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.572 ±(99.9%) 2.072 ops/ms [Average]
  (min, avg, max) = (8.456, 8.572, 8.683), stdev = 0.114
  CI (99.9%): [6.500, 10.644] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.780 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.004 ms/op
Iteration   1: 3.272 ±(99.9%) 0.002 ms/op
Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
Iteration   3: 3.070 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.157 ±(99.9%) 1.897 ms/op [Average]
  (min, avg, max) = (3.070, 3.157, 3.272), stdev = 0.104
  CI (99.9%): [1.259, 5.054] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.556 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.006 ms/op
Iteration   1: 2.965 ±(99.9%) 0.005 ms/op
Iteration   2: 3.018 ±(99.9%) 0.005 ms/op
Iteration   3: 3.078 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.020 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (2.965, 3.020, 3.078), stdev = 0.057
  CI (99.9%): [1.987, 4.054] (assumes normal distribution)


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
# Warmup Iteration   1: 7.830 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.003 ms/op
Iteration   1: 3.222 ±(99.9%) 0.003 ms/op
Iteration   2: 3.245 ±(99.9%) 0.004 ms/op
Iteration   3: 3.152 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.206 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.152, 3.206, 3.245), stdev = 0.049
  CI (99.9%): [2.320, 4.093] (assumes normal distribution)


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
# Warmup Iteration   1: 8.259 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.006 ms/op
Iteration   1: 3.755 ±(99.9%) 0.008 ms/op
Iteration   2: 3.692 ±(99.9%) 0.004 ms/op
Iteration   3: 3.667 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.705 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (3.667, 3.705, 3.755), stdev = 0.045
  CI (99.9%): [2.875, 4.534] (assumes normal distribution)


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
# Warmup Iteration   1: 7.501 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
Iteration   1: 3.294 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  11.092 ms/op
                 createUser·p0.9999: 21.833 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.997 ms/op
                 createUser·p0.999:  18.183 ms/op
                 createUser·p0.9999: 21.456 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  15.974 ms/op
                 createUser·p0.9999: 19.290 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298752
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15382 
    [ 2.500,  5.000) = 278256 
    [ 5.000,  7.500) = 4428 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     16.785 ms/op
     p(99.9900) =     21.336 ms/op
     p(99.9990) =     22.448 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 7.196 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.009 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 19.606 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 22.164 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 18.621 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 318793
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8702 
    [ 2.500,  5.000) = 306420 
    [ 5.000,  7.500) = 3081 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.420 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     11.374 ms/op
     p(99.9900) =     21.205 ms/op
     p(99.9990) =     22.434 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 7.712 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.010 ms/op
Iteration   1: 3.279 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  11.993 ms/op
                 getUser·p0.9999: 23.298 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  8.866 ms/op
                 getUser·p0.9999: 22.352 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  14.551 ms/op
                 getUser·p0.9999: 25.337 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294237
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20286 
    [ 2.500,  5.000) = 265974 
    [ 5.000,  7.500) = 6996 
    [ 7.500, 10.000) = 555 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     14.541 ms/op
     p(99.9900) =     23.898 ms/op
     p(99.9990) =     25.563 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 9.552 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.011 ms/op
Iteration   1: 3.825 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.265 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.858 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 17.128 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252191
  mean =      3.802 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 240946 
    [ 5.000,  7.500) = 8927 
    [ 7.500, 10.000) = 1467 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     14.595 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     21.346 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.029 ± 5.147  ops/ms
ClientPb.existUser                       thrpt       3  10.536 ± 3.471  ops/ms
ClientPb.getUser                         thrpt       3  10.263 ± 1.924  ops/ms
ClientPb.listUser                        thrpt       3   8.572 ± 2.072  ops/ms
ClientPb.createUser                       avgt       3   3.157 ± 1.897   ms/op
ClientPb.existUser                        avgt       3   3.020 ± 1.033   ms/op
ClientPb.getUser                          avgt       3   3.206 ± 0.887   ms/op
ClientPb.listUser                         avgt       3   3.705 ± 0.830   ms/op
ClientPb.createUser                     sample  298752   3.211 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.024           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.785           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.336           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.643           ms/op
ClientPb.existUser                      sample  318793   3.009 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.200           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.374           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.205           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.544           ms/op
ClientPb.getUser                        sample  294237   3.261 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.660           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.541           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.898           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  252191   3.802 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.534           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.595           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.431           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.627           ms/op
