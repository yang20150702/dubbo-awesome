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
# Warmup Iteration   1: 1.918 ops/ms
# Warmup Iteration   2: 4.474 ops/ms
# Warmup Iteration   3: 8.466 ops/ms
Iteration   1: 8.276 ops/ms
Iteration   2: 8.972 ops/ms
Iteration   3: 9.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.763 ±(99.9%) 7.724 ops/ms [Average]
  (min, avg, max) = (8.276, 8.763, 9.041), stdev = 0.423
  CI (99.9%): [1.039, 16.487] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.903 ops/ms
# Warmup Iteration   2: 8.662 ops/ms
# Warmup Iteration   3: 9.166 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 9.329 ops/ms
Iteration   3: 9.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.561 ±(99.9%) 3.912 ops/ms [Average]
  (min, avg, max) = (9.329, 9.561, 9.752), stdev = 0.214
  CI (99.9%): [5.649, 13.473] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.593 ops/ms
# Warmup Iteration   2: 7.902 ops/ms
# Warmup Iteration   3: 8.812 ops/ms
Iteration   1: 8.648 ops/ms
Iteration   2: 9.070 ops/ms
Iteration   3: 9.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.927 ±(99.9%) 4.402 ops/ms [Average]
  (min, avg, max) = (8.648, 8.927, 9.070), stdev = 0.241
  CI (99.9%): [4.525, 13.328] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.502 ops/ms
# Warmup Iteration   2: 6.728 ops/ms
# Warmup Iteration   3: 7.245 ops/ms
Iteration   1: 7.648 ops/ms
Iteration   2: 7.753 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.731 ±(99.9%) 1.352 ops/ms [Average]
  (min, avg, max) = (7.648, 7.731, 7.791), stdev = 0.074
  CI (99.9%): [6.379, 9.082] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.176 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.003 ms/op
Iteration   1: 3.493 ±(99.9%) 0.005 ms/op
Iteration   2: 3.551 ±(99.9%) 0.004 ms/op
Iteration   3: 3.475 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.506 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.475, 3.506, 3.551), stdev = 0.040
  CI (99.9%): [2.779, 4.234] (assumes normal distribution)


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
# Warmup Iteration   1: 10.053 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.004 ms/op
Iteration   1: 3.470 ±(99.9%) 0.008 ms/op
Iteration   2: 3.318 ±(99.9%) 0.005 ms/op
Iteration   3: 3.325 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.371 ±(99.9%) 1.566 ms/op [Average]
  (min, avg, max) = (3.318, 3.371, 3.470), stdev = 0.086
  CI (99.9%): [1.805, 4.937] (assumes normal distribution)


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
# Warmup Iteration   1: 9.618 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.008 ms/op
Iteration   1: 3.644 ±(99.9%) 0.006 ms/op
Iteration   2: 3.546 ±(99.9%) 0.005 ms/op
Iteration   3: 3.712 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.634 ±(99.9%) 1.529 ms/op [Average]
  (min, avg, max) = (3.546, 3.634, 3.712), stdev = 0.084
  CI (99.9%): [2.105, 5.163] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.347 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.009 ms/op
Iteration   1: 4.237 ±(99.9%) 0.006 ms/op
Iteration   2: 4.144 ±(99.9%) 0.010 ms/op
Iteration   3: 4.073 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.152 ±(99.9%) 1.503 ms/op [Average]
  (min, avg, max) = (4.073, 4.152, 4.237), stdev = 0.082
  CI (99.9%): [2.648, 5.655] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 12.027 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.016 ms/op
Iteration   1: 3.532 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  21.776 ms/op
                 createUser·p0.9999: 30.011 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   2: 3.614 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  23.740 ms/op
                 createUser·p0.9999: 28.284 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   3: 3.599 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  25.402 ms/op
                 createUser·p0.9999: 28.979 ms/op
                 createUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267733
  mean =      3.581 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5003 
    [ 2.500,  5.000) = 254512 
    [ 5.000,  7.500) = 6619 
    [ 7.500, 10.000) = 957 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     31.235 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 9.218 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.011 ms/op
Iteration   1: 3.402 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  11.222 ms/op
                 existUser·p0.9999: 24.654 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 3.638 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  23.525 ms/op
                 existUser·p0.9999: 31.444 ms/op
                 existUser·p1.00:   33.096 ms/op

Iteration   3: 3.429 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  24.324 ms/op
                 existUser·p0.9999: 43.867 ms/op
                 existUser·p1.00:   45.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275295
  mean =      3.487 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 264024 
    [ 5.000, 10.000) = 10544 
    [10.000, 15.000) = 461 
    [15.000, 20.000) = 10 
    [20.000, 25.000) = 84 
    [25.000, 30.000) = 112 
    [30.000, 35.000) = 28 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     14.241 ms/op
     p(99.9900) =     41.743 ms/op
     p(99.9990) =     44.335 ms/op
     p(99.9999) =     45.482 ms/op
    p(100.0000) =     45.482 ms/op


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
# Warmup Iteration   1: 10.224 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.012 ms/op
Iteration   1: 3.741 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.782 ms/op
                 getUser·p0.999:  21.168 ms/op
                 getUser·p0.9999: 26.783 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   2: 3.611 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  14.465 ms/op
                 getUser·p0.9999: 29.281 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   3: 3.549 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  23.066 ms/op
                 getUser·p0.9999: 31.096 ms/op
                 getUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264081
  mean =      3.632 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1560 
    [ 2.500,  5.000) = 247469 
    [ 5.000,  7.500) = 12585 
    [ 7.500, 10.000) = 1579 
    [10.000, 12.500) = 498 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     15.887 ms/op
     p(99.9900) =     30.349 ms/op
     p(99.9990) =     31.764 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 12.586 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.888 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.436 ±(99.9%) 0.017 ms/op
Iteration   1: 4.433 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   9.043 ms/op
                 listUser·p0.999:  23.526 ms/op
                 listUser·p0.9999: 26.171 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   2: 4.348 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 21.713 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.242 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 221221
  mean =      4.340 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 204219 
    [ 5.000,  7.500) = 12716 
    [ 7.500, 10.000) = 2925 
    [10.000, 12.500) = 704 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 206 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.735 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     17.484 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     27.249 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.763 ± 7.724  ops/ms
ClientPb.existUser                       thrpt       3   9.561 ± 3.912  ops/ms
ClientPb.getUser                         thrpt       3   8.927 ± 4.402  ops/ms
ClientPb.listUser                        thrpt       3   7.731 ± 1.352  ops/ms
ClientPb.createUser                       avgt       3   3.506 ± 0.727   ms/op
ClientPb.existUser                        avgt       3   3.371 ± 1.566   ms/op
ClientPb.getUser                          avgt       3   3.634 ± 1.529   ms/op
ClientPb.listUser                         avgt       3   4.152 ± 1.503   ms/op
ClientPb.createUser                     sample  267733   3.581 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.939           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.855           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.426           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.719           ms/op
ClientPb.existUser                      sample  275295   3.487 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.241           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.743           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.482           ms/op
ClientPb.getUser                        sample  264081   3.632 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.393           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.887           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.349           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.440           ms/op
ClientPb.listUser                       sample  221221   4.340 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.735           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.484           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.706           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.329           ms/op
