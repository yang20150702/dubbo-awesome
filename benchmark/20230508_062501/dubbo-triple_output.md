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
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 6.069 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 9.413 ops/ms
Iteration   2: 9.629 ops/ms
Iteration   3: 9.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.482 ±(99.9%) 2.327 ops/ms [Average]
  (min, avg, max) = (9.403, 9.482, 9.629), stdev = 0.128
  CI (99.9%): [7.155, 11.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.437 ops/ms
Iteration   1: 9.854 ops/ms
Iteration   2: 10.078 ops/ms
Iteration   3: 9.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.960 ±(99.9%) 2.048 ops/ms [Average]
  (min, avg, max) = (9.854, 9.960, 10.078), stdev = 0.112
  CI (99.9%): [7.912, 12.009] (assumes normal distribution)


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
# Warmup Iteration   1: 2.939 ops/ms
# Warmup Iteration   2: 8.576 ops/ms
# Warmup Iteration   3: 8.954 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 9.116 ops/ms
Iteration   3: 9.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.429 ±(99.9%) 5.290 ops/ms [Average]
  (min, avg, max) = (9.116, 9.429, 9.688), stdev = 0.290
  CI (99.9%): [4.139, 14.720] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.228 ops/ms
# Warmup Iteration   2: 7.458 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 8.045 ops/ms
Iteration   2: 8.307 ops/ms
Iteration   3: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.207 ±(99.9%) 2.578 ops/ms [Average]
  (min, avg, max) = (8.045, 8.207, 8.307), stdev = 0.141
  CI (99.9%): [5.628, 10.785] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.432 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.006 ms/op
Iteration   1: 3.365 ±(99.9%) 0.010 ms/op
Iteration   2: 3.283 ±(99.9%) 0.008 ms/op
Iteration   3: 3.369 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.339 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (3.283, 3.339, 3.369), stdev = 0.049
  CI (99.9%): [2.446, 4.232] (assumes normal distribution)


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
# Warmup Iteration   1: 7.833 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.005 ms/op
Iteration   1: 3.197 ±(99.9%) 0.002 ms/op
Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
Iteration   3: 3.155 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.160 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.127, 3.160, 3.197), stdev = 0.035
  CI (99.9%): [2.514, 3.806] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.745 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.006 ms/op
Iteration   1: 3.555 ±(99.9%) 0.004 ms/op
Iteration   2: 3.303 ±(99.9%) 0.006 ms/op
Iteration   3: 3.365 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.408 ±(99.9%) 2.389 ms/op [Average]
  (min, avg, max) = (3.303, 3.408, 3.555), stdev = 0.131
  CI (99.9%): [1.018, 5.797] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.476 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.008 ms/op
Iteration   1: 3.809 ±(99.9%) 0.014 ms/op
Iteration   2: 3.882 ±(99.9%) 0.013 ms/op
Iteration   3: 3.935 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.875 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.809, 3.875, 3.935), stdev = 0.063
  CI (99.9%): [2.729, 5.022] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.988 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
Iteration   1: 3.326 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  17.593 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.341 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  19.783 ms/op
                 createUser·p0.9999: 22.092 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.350 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  17.713 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287272
  mean =      3.339 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12025 
    [ 2.500,  5.000) = 270054 
    [ 5.000,  7.500) = 4376 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 150 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     17.718 ms/op
     p(99.9900) =     23.176 ms/op
     p(99.9990) =     24.048 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 8.133 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
Iteration   1: 3.271 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 28.286 ms/op
                 existUser·p1.00:   29.229 ms/op

Iteration   2: 3.206 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  13.369 ms/op
                 existUser·p0.9999: 25.495 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.466 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  9.696 ms/op
                 existUser·p0.9999: 25.631 ms/op
                 existUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295409
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14336 
    [ 2.500,  5.000) = 276423 
    [ 5.000,  7.500) = 3822 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 8.931 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.010 ms/op
Iteration   1: 3.359 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  20.512 ms/op
                 getUser·p0.9999: 23.855 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 3.422 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  20.795 ms/op
                 getUser·p0.9999: 27.754 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.608 ms/op
                 getUser·p0.999:  14.395 ms/op
                 getUser·p0.9999: 28.836 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285122
  mean =      3.365 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11204 
    [ 2.500,  5.000) = 266592 
    [ 5.000,  7.500) = 6073 
    [ 7.500, 10.000) = 749 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     18.145 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     29.178 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 10.691 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.014 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  19.678 ms/op
                 listUser·p0.9999: 24.458 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   2: 3.817 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 16.817 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 3.913 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.235 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247138
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 239680 
    [ 5.000,  7.500) = 5306 
    [ 7.500, 10.000) = 1335 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     14.757 ms/op
     p(99.9900) =     23.570 ms/op
     p(99.9990) =     25.021 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.482 ± 2.327  ops/ms
ClientPb.existUser                       thrpt       3   9.960 ± 2.048  ops/ms
ClientPb.getUser                         thrpt       3   9.429 ± 5.290  ops/ms
ClientPb.listUser                        thrpt       3   8.207 ± 2.578  ops/ms
ClientPb.createUser                       avgt       3   3.339 ± 0.893   ms/op
ClientPb.existUser                        avgt       3   3.160 ± 0.646   ms/op
ClientPb.getUser                          avgt       3   3.408 ± 2.389   ms/op
ClientPb.listUser                         avgt       3   3.875 ± 1.147   ms/op
ClientPb.createUser                     sample  287272   3.339 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.360           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.718           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.176           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.412           ms/op
ClientPb.existUser                      sample  295409   3.247 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.002           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.173           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.229           ms/op
ClientPb.getUser                        sample  285122   3.365 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.376           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.145           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.754           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.327           ms/op
ClientPb.listUser                       sample  247138   3.885 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.667           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.757           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.570           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.166           ms/op
