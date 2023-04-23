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
# Warmup Iteration   1: 2.333 ops/ms
# Warmup Iteration   2: 6.015 ops/ms
# Warmup Iteration   3: 8.990 ops/ms
Iteration   1: 9.373 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.472 ±(99.9%) 1.571 ops/ms [Average]
  (min, avg, max) = (9.373, 9.472, 9.534), stdev = 0.086
  CI (99.9%): [7.900, 11.043] (assumes normal distribution)


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
# Warmup Iteration   1: 3.074 ops/ms
# Warmup Iteration   2: 8.825 ops/ms
# Warmup Iteration   3: 9.457 ops/ms
Iteration   1: 9.691 ops/ms
Iteration   2: 10.065 ops/ms
Iteration   3: 9.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.791 ±(99.9%) 4.384 ops/ms [Average]
  (min, avg, max) = (9.616, 9.791, 10.065), stdev = 0.240
  CI (99.9%): [5.407, 14.175] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.845 ops/ms
# Warmup Iteration   2: 8.485 ops/ms
# Warmup Iteration   3: 9.288 ops/ms
Iteration   1: 9.659 ops/ms
Iteration   2: 9.651 ops/ms
Iteration   3: 9.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.615 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (9.535, 9.615, 9.659), stdev = 0.069
  CI (99.9%): [8.357, 10.873] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.834 ops/ms
# Warmup Iteration   2: 7.099 ops/ms
# Warmup Iteration   3: 7.719 ops/ms
Iteration   1: 7.862 ops/ms
Iteration   2: 8.287 ops/ms
Iteration   3: 8.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.168 ±(99.9%) 4.880 ops/ms [Average]
  (min, avg, max) = (7.862, 8.168, 8.355), stdev = 0.267
  CI (99.9%): [3.288, 13.047] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.095 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.001 ms/op
Iteration   1: 3.471 ±(99.9%) 0.004 ms/op
Iteration   2: 3.316 ±(99.9%) 0.015 ms/op
Iteration   3: 3.571 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.453 ±(99.9%) 2.343 ms/op [Average]
  (min, avg, max) = (3.316, 3.453, 3.571), stdev = 0.128
  CI (99.9%): [1.109, 5.796] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.454 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.007 ms/op
Iteration   1: 3.251 ±(99.9%) 0.003 ms/op
Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
Iteration   3: 3.292 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.279 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.251, 3.279, 3.294), stdev = 0.025
  CI (99.9%): [2.831, 3.727] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.106 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.007 ms/op
Iteration   1: 3.313 ±(99.9%) 0.011 ms/op
Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
Iteration   3: 3.324 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.318 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (3.313, 3.318, 3.324), stdev = 0.005
  CI (99.9%): [3.218, 3.417] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.449 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.010 ms/op
Iteration   1: 3.880 ±(99.9%) 0.012 ms/op
Iteration   2: 3.950 ±(99.9%) 0.014 ms/op
Iteration   3: 4.078 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.969 ±(99.9%) 1.834 ms/op [Average]
  (min, avg, max) = (3.880, 3.969, 4.078), stdev = 0.101
  CI (99.9%): [2.135, 5.803] (assumes normal distribution)


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
# Warmup Iteration   1: 9.829 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
Iteration   1: 3.426 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  19.574 ms/op
                 createUser·p0.9999: 25.767 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  21.430 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   3: 3.490 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  23.691 ms/op
                 createUser·p0.9999: 29.706 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277787
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14759 
    [ 2.500,  5.000) = 255620 
    [ 5.000,  7.500) = 6188 
    [ 7.500, 10.000) = 699 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     20.618 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.691 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
Iteration   1: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  11.004 ms/op
                 existUser·p0.9999: 22.648 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.220 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  10.004 ms/op
                 existUser·p0.9999: 27.861 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 3.335 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  19.561 ms/op
                 existUser·p0.9999: 24.470 ms/op
                 existUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294369
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14413 
    [ 2.500,  5.000) = 274003 
    [ 5.000,  7.500) = 5404 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.124 ms/op
     p(99.9900) =     26.855 ms/op
     p(99.9990) =     28.182 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 9.425 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.013 ms/op
Iteration   1: 3.459 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  22.446 ms/op
                 getUser·p0.9999: 26.395 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 3.420 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  21.430 ms/op
                 getUser·p0.9999: 25.951 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 3.444 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  18.576 ms/op
                 getUser·p0.9999: 26.435 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278701
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10489 
    [ 2.500,  5.000) = 259405 
    [ 5.000,  7.500) = 7689 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 144 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     20.126 ms/op
     p(99.9900) =     26.284 ms/op
     p(99.9990) =     27.048 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 9.342 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.371 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.012 ms/op
Iteration   1: 3.924 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  18.236 ms/op
                 listUser·p0.9999: 25.919 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   2: 4.145 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  15.725 ms/op
                 listUser·p0.9999: 16.220 ms/op
                 listUser·p1.00:   16.564 ms/op

Iteration   3: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 20.482 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237883
  mean =      4.030 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 229226 
    [ 5.000,  7.500) = 6338 
    [ 7.500, 10.000) = 1388 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     25.206 ms/op
     p(99.9990) =     26.300 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.472 ± 1.571  ops/ms
ClientPb.existUser                       thrpt       3   9.791 ± 4.384  ops/ms
ClientPb.getUser                         thrpt       3   9.615 ± 1.258  ops/ms
ClientPb.listUser                        thrpt       3   8.168 ± 4.880  ops/ms
ClientPb.createUser                       avgt       3   3.453 ± 2.343   ms/op
ClientPb.existUser                        avgt       3   3.279 ± 0.448   ms/op
ClientPb.getUser                          avgt       3   3.318 ± 0.100   ms/op
ClientPb.listUser                         avgt       3   3.969 ± 1.834   ms/op
ClientPb.createUser                     sample  277787   3.452 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.291           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.180           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  294369   3.259 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.022           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.124           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.855           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.279           ms/op
ClientPb.getUser                        sample  278701   3.441 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.126           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.284           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.361           ms/op
ClientPb.listUser                       sample  237883   4.030 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.485           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.007           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.206           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.870           ms/op
