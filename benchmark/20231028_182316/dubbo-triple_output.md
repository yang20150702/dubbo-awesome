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
# Warmup Iteration   1: 1.979 ops/ms
# Warmup Iteration   2: 5.019 ops/ms
# Warmup Iteration   3: 8.281 ops/ms
Iteration   1: 8.828 ops/ms
Iteration   2: 9.368 ops/ms
Iteration   3: 9.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.151 ±(99.9%) 5.208 ops/ms [Average]
  (min, avg, max) = (8.828, 9.151, 9.368), stdev = 0.285
  CI (99.9%): [3.943, 14.360] (assumes normal distribution)


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
# Warmup Iteration   1: 2.707 ops/ms
# Warmup Iteration   2: 8.173 ops/ms
# Warmup Iteration   3: 9.258 ops/ms
Iteration   1: 9.481 ops/ms
Iteration   2: 9.307 ops/ms
Iteration   3: 9.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.446 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (9.307, 9.446, 9.549), stdev = 0.125
  CI (99.9%): [7.164, 11.727] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.435 ops/ms
# Warmup Iteration   2: 7.180 ops/ms
# Warmup Iteration   3: 8.076 ops/ms
Iteration   1: 8.391 ops/ms
Iteration   2: 8.798 ops/ms
Iteration   3: 8.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.611 ±(99.9%) 3.742 ops/ms [Average]
  (min, avg, max) = (8.391, 8.611, 8.798), stdev = 0.205
  CI (99.9%): [4.869, 12.353] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.672 ops/ms
# Warmup Iteration   2: 7.064 ops/ms
# Warmup Iteration   3: 7.562 ops/ms
Iteration   1: 7.668 ops/ms
Iteration   2: 7.719 ops/ms
Iteration   3: 7.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.690 ±(99.9%) 0.473 ops/ms [Average]
  (min, avg, max) = (7.668, 7.690, 7.719), stdev = 0.026
  CI (99.9%): [7.217, 8.164] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.023 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.005 ms/op
Iteration   1: 3.549 ±(99.9%) 0.006 ms/op
Iteration   2: 3.560 ±(99.9%) 0.004 ms/op
Iteration   3: 3.529 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.546 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.529, 3.546, 3.560), stdev = 0.016
  CI (99.9%): [3.255, 3.838] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.133 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.004 ms/op
Iteration   1: 3.331 ±(99.9%) 0.004 ms/op
Iteration   2: 3.329 ±(99.9%) 0.006 ms/op
Iteration   3: 3.332 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.331 ±(99.9%) 0.036 ms/op [Average]
  (min, avg, max) = (3.329, 3.331, 3.332), stdev = 0.002
  CI (99.9%): [3.295, 3.366] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.936 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.003 ms/op
Iteration   1: 3.521 ±(99.9%) 0.003 ms/op
Iteration   2: 3.607 ±(99.9%) 0.003 ms/op
Iteration   3: 3.491 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.540 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (3.491, 3.540, 3.607), stdev = 0.061
  CI (99.9%): [2.435, 4.645] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.620 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.005 ms/op
Iteration   1: 4.190 ±(99.9%) 0.006 ms/op
Iteration   2: 4.147 ±(99.9%) 0.006 ms/op
Iteration   3: 4.091 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.143 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (4.091, 4.143, 4.190), stdev = 0.050
  CI (99.9%): [3.235, 5.051] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.873 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.010 ms/op
Iteration   1: 3.608 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  20.525 ms/op
                 createUser·p0.9999: 22.918 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.519 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 24.344 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 27.162 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269757
  mean =      3.556 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3109 
    [ 2.500,  5.000) = 259983 
    [ 5.000,  7.500) = 5289 
    [ 7.500, 10.000) = 708 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.310 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     20.201 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.363 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
Iteration   1: 3.366 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  10.959 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   7.315 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 23.201 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  20.596 ms/op
                 existUser·p0.9999: 26.616 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278325
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7145 
    [ 2.500,  5.000) = 263761 
    [ 5.000,  7.500) = 5973 
    [ 7.500, 10.000) = 775 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     19.683 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     28.118 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 11.391 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.013 ms/op
Iteration   1: 3.606 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  21.201 ms/op
                 getUser·p0.9999: 24.842 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.529 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  23.116 ms/op
                 getUser·p0.9999: 29.615 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   3: 3.572 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  21.115 ms/op
                 getUser·p0.9999: 29.590 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268991
  mean =      3.569 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3328 
    [ 2.500,  5.000) = 259099 
    [ 5.000,  7.500) = 5065 
    [ 7.500, 10.000) = 946 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     30.634 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 10.985 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.322 ±(99.9%) 0.013 ms/op
Iteration   1: 4.208 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.514 ms/op
                 listUser·p0.999:  21.561 ms/op
                 listUser·p0.9999: 24.209 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   2: 4.249 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 18.595 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.246 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.174 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226721
  mean =      4.234 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 216533 
    [ 5.000,  7.500) = 7749 
    [ 7.500, 10.000) = 1488 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 276 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     23.145 ms/op
     p(99.9990) =     24.960 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.151 ± 5.208  ops/ms
ClientPb.existUser                       thrpt       3   9.446 ± 2.281  ops/ms
ClientPb.getUser                         thrpt       3   8.611 ± 3.742  ops/ms
ClientPb.listUser                        thrpt       3   7.690 ± 0.473  ops/ms
ClientPb.createUser                       avgt       3   3.546 ± 0.292   ms/op
ClientPb.existUser                        avgt       3   3.331 ± 0.036   ms/op
ClientPb.getUser                          avgt       3   3.540 ± 1.105   ms/op
ClientPb.listUser                         avgt       3   4.143 ± 0.908   ms/op
ClientPb.createUser                     sample  269757   3.556 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.800           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.310           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.267           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.201           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.657           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  278325   3.448 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.973           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.683           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.526           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  268991   3.569 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.526           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.447           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.365           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.098           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.490           ms/op
ClientPb.listUser                       sample  226721   4.234 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.296           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.586           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.145           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.002           ms/op
