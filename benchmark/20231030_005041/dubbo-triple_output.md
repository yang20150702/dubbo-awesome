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
# Warmup Iteration   1: 2.374 ops/ms
# Warmup Iteration   2: 5.336 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 9.197 ops/ms
Iteration   2: 9.290 ops/ms
Iteration   3: 9.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.344 ±(99.9%) 3.282 ops/ms [Average]
  (min, avg, max) = (9.197, 9.344, 9.544), stdev = 0.180
  CI (99.9%): [6.062, 12.625] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.017 ops/ms
# Warmup Iteration   2: 8.710 ops/ms
# Warmup Iteration   3: 9.448 ops/ms
Iteration   1: 9.927 ops/ms
Iteration   2: 10.064 ops/ms
Iteration   3: 9.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.965 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (9.903, 9.965, 10.064), stdev = 0.087
  CI (99.9%): [8.382, 11.548] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.066 ops/ms
# Warmup Iteration   2: 8.343 ops/ms
# Warmup Iteration   3: 9.661 ops/ms
Iteration   1: 9.503 ops/ms
Iteration   2: 9.662 ops/ms
Iteration   3: 9.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.659 ±(99.9%) 2.822 ops/ms [Average]
  (min, avg, max) = (9.503, 9.659, 9.812), stdev = 0.155
  CI (99.9%): [6.837, 12.481] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.969 ops/ms
# Warmup Iteration   2: 7.537 ops/ms
# Warmup Iteration   3: 8.226 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 8.181 ops/ms
Iteration   3: 8.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.150 ±(99.9%) 1.058 ops/ms [Average]
  (min, avg, max) = (8.083, 8.150, 8.187), stdev = 0.058
  CI (99.9%): [7.092, 9.209] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.566 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.004 ms/op
Iteration   1: 3.291 ±(99.9%) 0.006 ms/op
Iteration   2: 3.239 ±(99.9%) 0.004 ms/op
Iteration   3: 3.234 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.254 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.234, 3.254, 3.291), stdev = 0.032
  CI (99.9%): [2.676, 3.833] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.728 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.003 ms/op
Iteration   1: 3.152 ±(99.9%) 0.004 ms/op
Iteration   2: 3.097 ±(99.9%) 0.004 ms/op
Iteration   3: 3.133 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.128 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.097, 3.128, 3.152), stdev = 0.028
  CI (99.9%): [2.621, 3.634] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.130 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.004 ms/op
Iteration   1: 3.249 ±(99.9%) 0.003 ms/op
Iteration   2: 3.395 ±(99.9%) 0.004 ms/op
Iteration   3: 3.309 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.317 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (3.249, 3.317, 3.395), stdev = 0.073
  CI (99.9%): [1.979, 4.656] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.760 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.005 ms/op
Iteration   1: 3.824 ±(99.9%) 0.006 ms/op
Iteration   2: 3.873 ±(99.9%) 0.005 ms/op
Iteration   3: 3.844 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.847 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.824, 3.847, 3.873), stdev = 0.025
  CI (99.9%): [3.396, 4.299] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.062 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.010 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  18.194 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.364 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  18.793 ms/op
                 createUser·p0.9999: 22.036 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 3.428 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  16.379 ms/op
                 createUser·p0.9999: 23.965 ms/op
                 createUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282366
  mean =      3.397 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15639 
    [ 2.500,  5.000) = 258257 
    [ 5.000,  7.500) = 6639 
    [ 7.500, 10.000) = 1203 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     16.591 ms/op
     p(99.9900) =     22.209 ms/op
     p(99.9990) =     25.041 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 8.493 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.277 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.142 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  15.955 ms/op
                 existUser·p0.9999: 20.700 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  14.149 ms/op
                 existUser·p0.9999: 24.307 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.322 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  18.032 ms/op
                 existUser·p0.9999: 22.950 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294507
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17306 
    [ 2.500,  5.000) = 269550 
    [ 5.000,  7.500) = 5909 
    [ 7.500, 10.000) = 1055 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     14.401 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     25.137 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 8.558 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.010 ms/op
Iteration   1: 3.371 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  17.730 ms/op
                 getUser·p0.9999: 21.089 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.356 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   7.651 ms/op
                 getUser·p0.999:  17.662 ms/op
                 getUser·p0.9999: 24.607 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   3: 3.237 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  12.017 ms/op
                 getUser·p0.9999: 24.453 ms/op
                 getUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288976
  mean =      3.320 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14731 
    [ 2.500,  5.000) = 265456 
    [ 5.000,  7.500) = 6757 
    [ 7.500, 10.000) = 1408 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     16.566 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     24.951 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 9.236 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.012 ms/op
Iteration   1: 3.864 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.849 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 19.226 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 3.758 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 14.959 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   3: 3.787 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.081 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.439 ms/op
                 listUser·p0.999:  14.291 ms/op
                 listUser·p0.9999: 27.158 ms/op
                 listUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252293
  mean =      3.803 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 147 
    [ 2.500,  5.000) = 243932 
    [ 5.000,  7.500) = 6168 
    [ 7.500, 10.000) = 1260 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     14.151 ms/op
     p(99.9900) =     19.227 ms/op
     p(99.9990) =     27.800 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.344 ± 3.282  ops/ms
ClientPb.existUser                       thrpt       3   9.965 ± 1.583  ops/ms
ClientPb.getUser                         thrpt       3   9.659 ± 2.822  ops/ms
ClientPb.listUser                        thrpt       3   8.150 ± 1.058  ops/ms
ClientPb.createUser                       avgt       3   3.254 ± 0.578   ms/op
ClientPb.existUser                        avgt       3   3.128 ± 0.507   ms/op
ClientPb.getUser                          avgt       3   3.317 ± 1.338   ms/op
ClientPb.listUser                         avgt       3   3.847 ± 0.451   ms/op
ClientPb.createUser                     sample  282366   3.397 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.944           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.591           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.209           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.133           ms/op
ClientPb.existUser                      sample  294507   3.258 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.631           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.401           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.462           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.231           ms/op
ClientPb.getUser                        sample  288976   3.320 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.566           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.347           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.199           ms/op
ClientPb.listUser                       sample  252293   3.803 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.151           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.227           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.017           ms/op
