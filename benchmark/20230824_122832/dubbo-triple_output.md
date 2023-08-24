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
# Warmup Iteration   1: 2.090 ops/ms
# Warmup Iteration   2: 5.575 ops/ms
# Warmup Iteration   3: 8.530 ops/ms
Iteration   1: 9.230 ops/ms
Iteration   2: 9.334 ops/ms
Iteration   3: 9.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.226 ±(99.9%) 2.011 ops/ms [Average]
  (min, avg, max) = (9.114, 9.226, 9.334), stdev = 0.110
  CI (99.9%): [7.215, 11.237] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.961 ops/ms
# Warmup Iteration   2: 8.834 ops/ms
# Warmup Iteration   3: 9.652 ops/ms
Iteration   1: 9.963 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.730 ±(99.9%) 3.866 ops/ms [Average]
  (min, avg, max) = (9.549, 9.730, 9.963), stdev = 0.212
  CI (99.9%): [5.864, 13.597] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.995 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 8.734 ops/ms
Iteration   1: 9.383 ops/ms
Iteration   2: 9.023 ops/ms
Iteration   3: 9.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.176 ±(99.9%) 3.395 ops/ms [Average]
  (min, avg, max) = (9.023, 9.176, 9.383), stdev = 0.186
  CI (99.9%): [5.781, 12.571] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.729 ops/ms
# Warmup Iteration   2: 7.282 ops/ms
# Warmup Iteration   3: 7.988 ops/ms
Iteration   1: 8.025 ops/ms
Iteration   2: 7.794 ops/ms
Iteration   3: 7.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.851 ±(99.9%) 2.805 ops/ms [Average]
  (min, avg, max) = (7.733, 7.851, 8.025), stdev = 0.154
  CI (99.9%): [5.046, 10.656] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.014 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.006 ms/op
Iteration   1: 3.337 ±(99.9%) 0.010 ms/op
Iteration   2: 3.474 ±(99.9%) 0.006 ms/op
Iteration   3: 3.371 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.394 ±(99.9%) 1.297 ms/op [Average]
  (min, avg, max) = (3.337, 3.394, 3.474), stdev = 0.071
  CI (99.9%): [2.097, 4.691] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.643 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.004 ms/op
Iteration   1: 3.247 ±(99.9%) 0.003 ms/op
Iteration   2: 3.281 ±(99.9%) 0.004 ms/op
Iteration   3: 3.420 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.316 ±(99.9%) 1.666 ms/op [Average]
  (min, avg, max) = (3.247, 3.316, 3.420), stdev = 0.091
  CI (99.9%): [1.650, 4.982] (assumes normal distribution)


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
# Warmup Iteration   1: 9.869 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.004 ms/op
Iteration   1: 3.447 ±(99.9%) 0.007 ms/op
Iteration   2: 3.412 ±(99.9%) 0.005 ms/op
Iteration   3: 3.377 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.412 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.377, 3.412, 3.447), stdev = 0.035
  CI (99.9%): [2.773, 4.051] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.835 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.008 ms/op
Iteration   1: 4.054 ±(99.9%) 0.009 ms/op
Iteration   2: 4.026 ±(99.9%) 0.009 ms/op
Iteration   3: 4.038 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.040 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (4.026, 4.040, 4.054), stdev = 0.014
  CI (99.9%): [3.782, 4.297] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.445 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.011 ms/op
Iteration   1: 3.514 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.471 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  21.423 ms/op
                 createUser·p0.9999: 24.110 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   3: 3.437 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  21.666 ms/op
                 createUser·p0.9999: 50.135 ms/op
                 createUser·p1.00:   50.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276051
  mean =      3.474 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 265401 
    [ 5.000, 10.000) = 10029 
    [10.000, 15.000) = 288 
    [15.000, 20.000) = 59 
    [20.000, 25.000) = 240 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 19 
    [50.000, 55.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     19.987 ms/op
     p(99.9900) =     48.431 ms/op
     p(99.9990) =     50.347 ms/op
     p(99.9999) =     50.594 ms/op
    p(100.0000) =     50.594 ms/op


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
# Warmup Iteration   1: 8.291 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.009 ms/op
Iteration   1: 3.389 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  10.988 ms/op
                 existUser·p0.9999: 30.619 ms/op
                 existUser·p1.00:   31.326 ms/op

Iteration   2: 3.346 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  19.337 ms/op
                 existUser·p0.9999: 31.435 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  19.268 ms/op
                 existUser·p0.9999: 27.903 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284575
  mean =      3.371 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10846 
    [ 2.500,  5.000) = 265573 
    [ 5.000,  7.500) = 6835 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     30.918 ms/op
     p(99.9990) =     32.226 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 9.035 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.012 ms/op
Iteration   1: 3.495 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.333 ms/op
                 getUser·p0.999:  21.400 ms/op
                 getUser·p0.9999: 33.145 ms/op
                 getUser·p1.00:   33.391 ms/op

Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  20.853 ms/op
                 getUser·p0.9999: 26.096 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.411 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  20.066 ms/op
                 getUser·p0.9999: 31.687 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281533
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5763 
    [ 2.500,  5.000) = 266624 
    [ 5.000,  7.500) = 7389 
    [ 7.500, 10.000) = 1305 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     20.168 ms/op
     p(99.9900) =     31.891 ms/op
     p(99.9990) =     33.278 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 11.094 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.015 ms/op
Iteration   1: 4.071 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 27.530 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 18.543 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 4.046 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237773
  mean =      4.037 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 225945 
    [ 5.000,  7.500) = 8891 
    [ 7.500, 10.000) = 1800 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.743 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     25.654 ms/op
     p(99.9990) =     28.295 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.226 ± 2.011  ops/ms
ClientPb.existUser                       thrpt       3   9.730 ± 3.866  ops/ms
ClientPb.getUser                         thrpt       3   9.176 ± 3.395  ops/ms
ClientPb.listUser                        thrpt       3   7.851 ± 2.805  ops/ms
ClientPb.createUser                       avgt       3   3.394 ± 1.297   ms/op
ClientPb.existUser                        avgt       3   3.316 ± 1.666   ms/op
ClientPb.getUser                          avgt       3   3.412 ± 0.639   ms/op
ClientPb.listUser                         avgt       3   4.040 ± 0.257   ms/op
ClientPb.createUser                     sample  276051   3.474 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.972           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.987           ms/op
ClientPb.createUser:createUser·p0.9999  sample          48.431           ms/op
ClientPb.createUser:createUser·p1.00    sample          50.594           ms/op
ClientPb.existUser                      sample  284575   3.371 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.075           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.918           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.375           ms/op
ClientPb.getUser                        sample  281533   3.410 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.178           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.168           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.391           ms/op
ClientPb.listUser                       sample  237773   4.037 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.905           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.654           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
