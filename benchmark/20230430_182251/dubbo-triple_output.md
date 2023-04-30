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
# Warmup Iteration   1: 1.181 ops/ms
# Warmup Iteration   2: 2.474 ops/ms
# Warmup Iteration   3: 5.664 ops/ms
Iteration   1: 5.769 ops/ms
Iteration   2: 6.174 ops/ms
Iteration   3: 6.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.090 ±(99.9%) 5.263 ops/ms [Average]
  (min, avg, max) = (5.769, 6.090, 6.327), stdev = 0.288
  CI (99.9%): [0.828, 11.353] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.843 ops/ms
# Warmup Iteration   2: 5.176 ops/ms
# Warmup Iteration   3: 6.258 ops/ms
Iteration   1: 6.429 ops/ms
Iteration   2: 6.354 ops/ms
Iteration   3: 6.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.333 ±(99.9%) 1.970 ops/ms [Average]
  (min, avg, max) = (6.217, 6.333, 6.429), stdev = 0.108
  CI (99.9%): [4.364, 8.303] (assumes normal distribution)


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
# Warmup Iteration   1: 1.639 ops/ms
# Warmup Iteration   2: 4.850 ops/ms
# Warmup Iteration   3: 6.176 ops/ms
Iteration   1: 6.358 ops/ms
Iteration   2: 6.032 ops/ms
Iteration   3: 6.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.201 ±(99.9%) 2.975 ops/ms [Average]
  (min, avg, max) = (6.032, 6.201, 6.358), stdev = 0.163
  CI (99.9%): [3.226, 9.177] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.610 ops/ms
# Warmup Iteration   2: 4.063 ops/ms
# Warmup Iteration   3: 5.092 ops/ms
Iteration   1: 5.185 ops/ms
Iteration   2: 5.141 ops/ms
Iteration   3: 5.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.239 ±(99.9%) 2.435 ops/ms [Average]
  (min, avg, max) = (5.141, 5.239, 5.391), stdev = 0.133
  CI (99.9%): [2.804, 7.674] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.370 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.413 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.533 ±(99.9%) 0.015 ms/op
Iteration   1: 5.189 ±(99.9%) 0.015 ms/op
Iteration   2: 5.094 ±(99.9%) 0.008 ms/op
Iteration   3: 5.106 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.130 ±(99.9%) 0.947 ms/op [Average]
  (min, avg, max) = (5.094, 5.130, 5.189), stdev = 0.052
  CI (99.9%): [4.182, 6.077] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.227 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.338 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.242 ±(99.9%) 0.005 ms/op
Iteration   1: 4.965 ±(99.9%) 0.008 ms/op
Iteration   2: 5.062 ±(99.9%) 0.008 ms/op
Iteration   3: 5.089 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.039 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (4.965, 5.039, 5.089), stdev = 0.066
  CI (99.9%): [3.842, 6.235] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.266 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.955 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.131 ±(99.9%) 0.018 ms/op
Iteration   1: 5.547 ±(99.9%) 0.010 ms/op
Iteration   2: 5.159 ±(99.9%) 0.009 ms/op
Iteration   3: 5.208 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.305 ±(99.9%) 3.852 ms/op [Average]
  (min, avg, max) = (5.159, 5.305, 5.547), stdev = 0.211
  CI (99.9%): [1.453, 9.157] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.199 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.992 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 6.056 ±(99.9%) 0.016 ms/op
Iteration   1: 6.001 ±(99.9%) 0.006 ms/op
Iteration   2: 5.707 ±(99.9%) 0.019 ms/op
Iteration   3: 5.764 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.824 ±(99.9%) 2.842 ms/op [Average]
  (min, avg, max) = (5.707, 5.824, 6.001), stdev = 0.156
  CI (99.9%): [2.981, 8.666] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.421 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.180 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.827 ±(99.9%) 0.029 ms/op
Iteration   1: 5.531 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.277 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  25.699 ms/op
                 createUser·p0.9999: 28.286 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   2: 5.161 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.458 ms/op
                 createUser·p0.50:   5.104 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   6.955 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  23.825 ms/op
                 createUser·p0.9999: 30.568 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   3: 5.257 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.032 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   6.939 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  26.086 ms/op
                 createUser·p0.9999: 30.534 ms/op
                 createUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180723
  mean =      5.312 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 78335 
    [ 5.000,  7.500) = 95013 
    [ 7.500, 10.000) = 6165 
    [10.000, 12.500) = 675 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.274 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     24.520 ms/op
     p(99.9900) =     30.209 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.625 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.947 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.308 ±(99.9%) 0.019 ms/op
Iteration   1: 5.080 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  21.697 ms/op
                 existUser·p0.9999: 30.356 ms/op
                 existUser·p1.00:   32.080 ms/op

Iteration   2: 5.054 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.621 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   6.889 ms/op
                 existUser·p0.99:   9.683 ms/op
                 existUser·p0.999:  23.776 ms/op
                 existUser·p0.9999: 29.901 ms/op
                 existUser·p1.00:   30.376 ms/op

Iteration   3: 5.157 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.046 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   9.696 ms/op
                 existUser·p0.999:  21.835 ms/op
                 existUser·p0.9999: 37.737 ms/op
                 existUser·p1.00:   43.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187988
  mean =      5.097 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 103691 
    [ 5.000, 10.000) = 82812 
    [10.000, 15.000) = 1231 
    [15.000, 20.000) = 51 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 107 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.046 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     21.824 ms/op
     p(99.9900) =     30.324 ms/op
     p(99.9990) =     38.441 ms/op
     p(99.9999) =     43.516 ms/op
    p(100.0000) =     43.516 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.048 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 5.960 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.499 ±(99.9%) 0.023 ms/op
Iteration   1: 5.110 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.277 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.168 ms/op
                 getUser·p0.99:   9.683 ms/op
                 getUser·p0.999:  23.498 ms/op
                 getUser·p0.9999: 30.661 ms/op
                 getUser·p1.00:   35.979 ms/op

Iteration   2: 5.271 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.400 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.463 ms/op
                 getUser·p0.99:   11.918 ms/op
                 getUser·p0.999:  25.124 ms/op
                 getUser·p0.9999: 30.212 ms/op
                 getUser·p1.00:   32.047 ms/op

Iteration   3: 5.285 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   7.274 ms/op
                 getUser·p0.99:   9.880 ms/op
                 getUser·p0.999:  24.838 ms/op
                 getUser·p0.9999: 28.474 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183715
  mean =      5.221 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 95653 
    [ 5.000,  7.500) = 80320 
    [ 7.500, 10.000) = 5429 
    [10.000, 12.500) = 1399 
    [12.500, 15.000) = 466 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.291 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     24.304 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     35.540 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.816 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.062 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 6.133 ±(99.9%) 0.022 ms/op
Iteration   1: 5.844 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  25.563 ms/op
                 listUser·p0.9999: 28.661 ms/op
                 listUser·p1.00:   30.015 ms/op

Iteration   2: 6.017 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.646 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   10.609 ms/op
                 listUser·p0.999:  21.594 ms/op
                 listUser·p0.9999: 24.864 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 6.009 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  20.349 ms/op
                 listUser·p0.9999: 24.773 ms/op
                 listUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161051
  mean =      5.956 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 40251 
    [ 5.000,  7.500) = 104932 
    [ 7.500, 10.000) = 13266 
    [10.000, 12.500) = 1720 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      7.479 ms/op
     p(95.0000) =      8.364 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     21.592 ms/op
     p(99.9900) =     27.292 ms/op
     p(99.9990) =     29.895 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.090 ± 5.263  ops/ms
ClientPb.existUser                       thrpt       3   6.333 ± 1.970  ops/ms
ClientPb.getUser                         thrpt       3   6.201 ± 2.975  ops/ms
ClientPb.listUser                        thrpt       3   5.239 ± 2.435  ops/ms
ClientPb.createUser                       avgt       3   5.130 ± 0.947   ms/op
ClientPb.existUser                        avgt       3   5.039 ± 1.197   ms/op
ClientPb.getUser                          avgt       3   5.305 ± 3.852   ms/op
ClientPb.listUser                         avgt       3   5.824 ± 2.842   ms/op
ClientPb.createUser                     sample  180723   5.312 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.032           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.554           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.274           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.322           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.209           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.785           ms/op
ClientPb.existUser                      sample  187988   5.097 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.046           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.874           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.568           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.824           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.324           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.516           ms/op
ClientPb.getUser                        sample  183715   5.221 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.948           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.291           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.535           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.304           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.048           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.979           ms/op
ClientPb.listUser                       sample  161051   5.956 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.448           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.364           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.813           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.592           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.292           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.015           ms/op
