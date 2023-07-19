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
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 5.166 ops/ms
# Warmup Iteration   3: 8.795 ops/ms
Iteration   1: 9.630 ops/ms
Iteration   2: 9.785 ops/ms
Iteration   3: 9.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.719 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (9.630, 9.719, 9.785), stdev = 0.080
  CI (99.9%): [8.266, 11.171] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.516 ops/ms
# Warmup Iteration   2: 9.316 ops/ms
# Warmup Iteration   3: 10.240 ops/ms
Iteration   1: 10.188 ops/ms
Iteration   2: 9.993 ops/ms
Iteration   3: 10.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.152 ±(99.9%) 2.640 ops/ms [Average]
  (min, avg, max) = (9.993, 10.152, 10.275), stdev = 0.145
  CI (99.9%): [7.512, 12.792] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.199 ops/ms
# Warmup Iteration   2: 8.479 ops/ms
# Warmup Iteration   3: 9.578 ops/ms
Iteration   1: 9.449 ops/ms
Iteration   2: 9.523 ops/ms
Iteration   3: 9.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.579 ±(99.9%) 3.013 ops/ms [Average]
  (min, avg, max) = (9.449, 9.579, 9.765), stdev = 0.165
  CI (99.9%): [6.566, 12.591] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.334 ops/ms
# Warmup Iteration   2: 7.536 ops/ms
# Warmup Iteration   3: 8.187 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 8.105 ops/ms
Iteration   3: 8.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.091 ±(99.9%) 1.620 ops/ms [Average]
  (min, avg, max) = (7.997, 8.091, 8.173), stdev = 0.089
  CI (99.9%): [6.472, 9.711] (assumes normal distribution)


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
# Warmup Iteration   1: 9.554 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.005 ms/op
Iteration   1: 3.340 ±(99.9%) 0.006 ms/op
Iteration   2: 3.219 ±(99.9%) 0.010 ms/op
Iteration   3: 3.273 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.278 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.219, 3.278, 3.340), stdev = 0.061
  CI (99.9%): [2.165, 4.390] (assumes normal distribution)


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
# Warmup Iteration   1: 9.487 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.006 ms/op
Iteration   1: 3.297 ±(99.9%) 0.006 ms/op
Iteration   2: 3.060 ±(99.9%) 0.004 ms/op
Iteration   3: 3.122 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.160 ±(99.9%) 2.247 ms/op [Average]
  (min, avg, max) = (3.060, 3.160, 3.297), stdev = 0.123
  CI (99.9%): [0.913, 5.407] (assumes normal distribution)


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
# Warmup Iteration   1: 8.389 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.003 ms/op
Iteration   1: 3.222 ±(99.9%) 0.004 ms/op
Iteration   2: 3.265 ±(99.9%) 0.006 ms/op
Iteration   3: 3.780 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.422 ±(99.9%) 5.661 ms/op [Average]
  (min, avg, max) = (3.222, 3.422, 3.780), stdev = 0.310
  CI (99.9%): [≈ 0, 9.083] (assumes normal distribution)


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
# Warmup Iteration   1: 8.970 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.009 ms/op
Iteration   1: 3.785 ±(99.9%) 0.009 ms/op
Iteration   2: 3.851 ±(99.9%) 0.013 ms/op
Iteration   3: 3.865 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.834 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (3.785, 3.834, 3.865), stdev = 0.043
  CI (99.9%): [3.053, 4.614] (assumes normal distribution)


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
# Warmup Iteration   1: 8.753 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.011 ms/op
Iteration   1: 3.243 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  10.295 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   2: 3.167 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  20.611 ms/op
                 createUser·p0.9999: 29.649 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  15.633 ms/op
                 createUser·p0.9999: 23.335 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298315
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11964 
    [ 2.500,  5.000) = 280481 
    [ 5.000,  7.500) = 5038 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 7.856 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.010 ms/op
Iteration   1: 3.170 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  10.928 ms/op
                 existUser·p0.9999: 20.831 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  15.264 ms/op
                 existUser·p0.9999: 27.193 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.331 ms/op
                 existUser·p0.9999: 30.972 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303612
  mean =      3.160 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18997 
    [ 2.500,  5.000) = 278561 
    [ 5.000,  7.500) = 5388 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.197 ms/op
     p(99.9900) =     29.182 ms/op
     p(99.9990) =     31.488 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 9.209 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.010 ms/op
Iteration   1: 3.258 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  16.613 ms/op
                 getUser·p0.9999: 20.524 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 3.262 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  14.350 ms/op
                 getUser·p0.9999: 22.885 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 23.011 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294029
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3654 
    [ 2.500,  5.000) = 281999 
    [ 5.000,  7.500) = 7259 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     16.301 ms/op
     p(99.9900) =     22.564 ms/op
     p(99.9990) =     24.152 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 9.262 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.012 ms/op
Iteration   1: 3.790 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 16.389 ms/op
                 listUser·p1.00:   16.613 ms/op

Iteration   3: 3.839 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.822 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248250
  mean =      3.865 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 238662 
    [ 5.000,  7.500) = 7609 
    [ 7.500, 10.000) = 1150 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 330 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.159 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     19.943 ms/op
     p(99.9990) =     22.116 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.719 ± 1.453  ops/ms
ClientPb.existUser                       thrpt       3  10.152 ± 2.640  ops/ms
ClientPb.getUser                         thrpt       3   9.579 ± 3.013  ops/ms
ClientPb.listUser                        thrpt       3   8.091 ± 1.620  ops/ms
ClientPb.createUser                       avgt       3   3.278 ± 1.112   ms/op
ClientPb.existUser                        avgt       3   3.160 ± 2.247   ms/op
ClientPb.getUser                          avgt       3   3.422 ± 5.661   ms/op
ClientPb.listUser                         avgt       3   3.834 ± 0.781   ms/op
ClientPb.createUser                     sample  298315   3.215 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.105           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.951           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.179           ms/op
ClientPb.existUser                      sample  303612   3.160 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.197           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  294029   3.264 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.331           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.301           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.564           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.216           ms/op
ClientPb.listUser                       sample  248250   3.865 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.159           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.943           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.839           ms/op
