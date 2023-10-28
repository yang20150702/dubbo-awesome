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
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 4.355 ops/ms
# Warmup Iteration   3: 8.494 ops/ms
Iteration   1: 8.987 ops/ms
Iteration   2: 9.054 ops/ms
Iteration   3: 9.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.100 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (8.987, 9.100, 9.261), stdev = 0.143
  CI (99.9%): [6.497, 11.704] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.003 ops/ms
# Warmup Iteration   2: 9.015 ops/ms
# Warmup Iteration   3: 9.574 ops/ms
Iteration   1: 9.793 ops/ms
Iteration   2: 9.713 ops/ms
Iteration   3: 9.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.792 ±(99.9%) 1.426 ops/ms [Average]
  (min, avg, max) = (9.713, 9.792, 9.869), stdev = 0.078
  CI (99.9%): [8.366, 11.218] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.095 ops/ms
# Warmup Iteration   2: 8.604 ops/ms
# Warmup Iteration   3: 8.855 ops/ms
Iteration   1: 9.420 ops/ms
Iteration   2: 9.224 ops/ms
Iteration   3: 9.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.340 ±(99.9%) 1.879 ops/ms [Average]
  (min, avg, max) = (9.224, 9.340, 9.420), stdev = 0.103
  CI (99.9%): [7.462, 11.219] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.743 ops/ms
# Warmup Iteration   2: 7.065 ops/ms
# Warmup Iteration   3: 7.563 ops/ms
Iteration   1: 7.702 ops/ms
Iteration   2: 7.746 ops/ms
Iteration   3: 7.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.761 ±(99.9%) 1.230 ops/ms [Average]
  (min, avg, max) = (7.702, 7.761, 7.834), stdev = 0.067
  CI (99.9%): [6.530, 8.991] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.496 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.004 ms/op
Iteration   1: 3.456 ±(99.9%) 0.004 ms/op
Iteration   2: 3.579 ±(99.9%) 0.004 ms/op
Iteration   3: 3.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.514 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (3.456, 3.514, 3.579), stdev = 0.062
  CI (99.9%): [2.383, 4.645] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.201 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.004 ms/op
Iteration   1: 3.368 ±(99.9%) 0.005 ms/op
Iteration   2: 3.352 ±(99.9%) 0.006 ms/op
Iteration   3: 3.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.380 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.352, 3.380, 3.420), stdev = 0.035
  CI (99.9%): [2.737, 4.023] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.366 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.002 ms/op
Iteration   1: 3.417 ±(99.9%) 0.004 ms/op
Iteration   2: 3.439 ±(99.9%) 0.004 ms/op
Iteration   3: 3.460 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.439 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.417, 3.439, 3.460), stdev = 0.021
  CI (99.9%): [3.050, 3.828] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.597 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.005 ms/op
Iteration   1: 4.131 ±(99.9%) 0.005 ms/op
Iteration   2: 4.102 ±(99.9%) 0.005 ms/op
Iteration   3: 4.117 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.116 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (4.102, 4.116, 4.131), stdev = 0.015
  CI (99.9%): [3.848, 4.385] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.508 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.009 ms/op
Iteration   1: 3.489 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.913 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   2: 3.529 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  24.199 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   3: 3.461 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.524 ms/op
                 createUser·p0.999:  20.399 ms/op
                 createUser·p0.9999: 25.707 ms/op
                 createUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274601
  mean =      3.493 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2257 
    [ 2.500,  5.000) = 266976 
    [ 5.000,  7.500) = 4111 
    [ 7.500, 10.000) = 602 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.996 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     30.049 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.465 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.008 ms/op
Iteration   1: 3.347 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.052 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  18.497 ms/op
                 existUser·p0.9999: 21.722 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   2: 3.425 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.894 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  12.824 ms/op
                 existUser·p0.9999: 25.647 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  18.736 ms/op
                 existUser·p0.9999: 24.574 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284178
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12090 
    [ 2.500,  5.000) = 267668 
    [ 5.000,  7.500) = 3369 
    [ 7.500, 10.000) = 328 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.063 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.250 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.012 ms/op
Iteration   1: 3.667 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   7.782 ms/op
                 getUser·p0.999:  21.889 ms/op
                 getUser·p0.9999: 46.042 ms/op
                 getUser·p1.00:   47.055 ms/op

Iteration   2: 3.484 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  22.479 ms/op
                 getUser·p0.9999: 26.178 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 27.948 ms/op
                 getUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270190
  mean =      3.553 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 260775 
    [ 5.000, 10.000) = 8805 
    [10.000, 15.000) = 253 
    [15.000, 20.000) = 17 
    [20.000, 25.000) = 258 
    [25.000, 30.000) = 55 
    [30.000, 35.000) = 15 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     21.660 ms/op
     p(99.9900) =     30.953 ms/op
     p(99.9990) =     46.878 ms/op
     p(99.9999) =     47.055 ms/op
    p(100.0000) =     47.055 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.470 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.575 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.013 ms/op
Iteration   1: 4.227 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   4.121 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.252 ms/op
                 listUser·p0.999:  21.343 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 4.158 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  16.091 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.154 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229482
  mean =      4.180 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 220927 
    [ 5.000,  7.500) = 6642 
    [ 7.500, 10.000) = 1055 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     16.720 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.472 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.100 ± 2.604  ops/ms
ClientPb.existUser                       thrpt       3   9.792 ± 1.426  ops/ms
ClientPb.getUser                         thrpt       3   9.340 ± 1.879  ops/ms
ClientPb.listUser                        thrpt       3   7.761 ± 1.230  ops/ms
ClientPb.createUser                       avgt       3   3.514 ± 1.131   ms/op
ClientPb.existUser                        avgt       3   3.380 ± 0.643   ms/op
ClientPb.getUser                          avgt       3   3.439 ± 0.389   ms/op
ClientPb.listUser                         avgt       3   4.116 ± 0.269   ms/op
ClientPb.createUser                     sample  274601   3.493 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.159           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.996           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.480           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.345           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.343           ms/op
ClientPb.existUser                      sample  284178   3.376 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.427           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.009           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.608           ms/op
ClientPb.getUser                        sample  270190   3.553 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.358           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.660           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.953           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.055           ms/op
ClientPb.listUser                       sample  229482   4.180 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.720           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.101           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.871           ms/op
