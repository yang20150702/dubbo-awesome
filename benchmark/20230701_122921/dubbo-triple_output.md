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
# Warmup Iteration   1: 2.017 ops/ms
# Warmup Iteration   2: 5.389 ops/ms
# Warmup Iteration   3: 8.548 ops/ms
Iteration   1: 8.808 ops/ms
Iteration   2: 9.274 ops/ms
Iteration   3: 9.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.124 ±(99.9%) 4.983 ops/ms [Average]
  (min, avg, max) = (8.808, 9.124, 9.288), stdev = 0.273
  CI (99.9%): [4.140, 14.107] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.828 ops/ms
# Warmup Iteration   2: 8.279 ops/ms
# Warmup Iteration   3: 9.572 ops/ms
Iteration   1: 9.926 ops/ms
Iteration   2: 9.550 ops/ms
Iteration   3: 9.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.641 ±(99.9%) 4.602 ops/ms [Average]
  (min, avg, max) = (9.447, 9.641, 9.926), stdev = 0.252
  CI (99.9%): [5.039, 14.243] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.534 ops/ms
# Warmup Iteration   2: 7.690 ops/ms
# Warmup Iteration   3: 8.696 ops/ms
Iteration   1: 9.005 ops/ms
Iteration   2: 9.407 ops/ms
Iteration   3: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.271 ±(99.9%) 4.195 ops/ms [Average]
  (min, avg, max) = (9.005, 9.271, 9.407), stdev = 0.230
  CI (99.9%): [5.076, 13.466] (assumes normal distribution)


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
# Warmup Iteration   1: 2.497 ops/ms
# Warmup Iteration   2: 7.094 ops/ms
# Warmup Iteration   3: 7.753 ops/ms
Iteration   1: 7.649 ops/ms
Iteration   2: 8.097 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.965 ±(99.9%) 5.017 ops/ms [Average]
  (min, avg, max) = (7.649, 7.965, 8.149), stdev = 0.275
  CI (99.9%): [2.947, 12.982] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.019 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.005 ms/op
Iteration   1: 3.599 ±(99.9%) 0.009 ms/op
Iteration   2: 3.428 ±(99.9%) 0.006 ms/op
Iteration   3: 3.364 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.464 ±(99.9%) 2.216 ms/op [Average]
  (min, avg, max) = (3.364, 3.464, 3.599), stdev = 0.121
  CI (99.9%): [1.247, 5.680] (assumes normal distribution)


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
# Warmup Iteration   1: 8.224 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.007 ms/op
Iteration   1: 3.322 ±(99.9%) 0.006 ms/op
Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
Iteration   3: 3.298 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.319 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.298, 3.319, 3.339), stdev = 0.021
  CI (99.9%): [2.944, 3.695] (assumes normal distribution)


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
# Warmup Iteration   1: 10.613 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.005 ms/op
Iteration   1: 3.806 ±(99.9%) 0.005 ms/op
Iteration   2: 3.537 ±(99.9%) 0.008 ms/op
Iteration   3: 3.661 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.668 ±(99.9%) 2.460 ms/op [Average]
  (min, avg, max) = (3.537, 3.668, 3.806), stdev = 0.135
  CI (99.9%): [1.207, 6.128] (assumes normal distribution)


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
# Warmup Iteration   1: 12.675 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.008 ms/op
Iteration   1: 4.182 ±(99.9%) 0.009 ms/op
Iteration   2: 4.118 ±(99.9%) 0.010 ms/op
Iteration   3: 4.105 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.135 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (4.105, 4.135, 4.182), stdev = 0.041
  CI (99.9%): [3.386, 4.883] (assumes normal distribution)


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
# Warmup Iteration   1: 12.263 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.017 ms/op
Iteration   1: 3.689 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.185 ms/op
                 createUser·p0.999:  23.364 ms/op
                 createUser·p0.9999: 26.029 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   2: 3.631 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.442 ms/op
                 createUser·p0.999:  24.770 ms/op
                 createUser·p0.9999: 29.064 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 3.561 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.353 ms/op
                 createUser·p0.999:  20.845 ms/op
                 createUser·p0.9999: 30.606 ms/op
                 createUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264620
  mean =      3.626 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6680 
    [ 2.500,  5.000) = 248075 
    [ 5.000,  7.500) = 8208 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     22.586 ms/op
     p(99.9900) =     29.705 ms/op
     p(99.9990) =     30.760 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.008 ms/op
Iteration   1: 3.357 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  10.449 ms/op
                 existUser·p0.9999: 29.655 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   2: 3.264 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.564 ms/op
                 existUser·p0.999:  14.192 ms/op
                 existUser·p0.9999: 25.736 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 27.144 ms/op
                 existUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291429
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18706 
    [ 2.500,  5.000) = 267689 
    [ 5.000,  7.500) = 4071 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     27.815 ms/op
     p(99.9990) =     29.789 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 10.112 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.011 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.974 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  21.009 ms/op
                 getUser·p0.9999: 24.342 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   2: 3.461 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  23.331 ms/op
                 getUser·p0.9999: 25.674 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.482 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  19.807 ms/op
                 getUser·p0.9999: 26.444 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275756
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2521 
    [ 2.500,  5.000) = 264515 
    [ 5.000,  7.500) = 7589 
    [ 7.500, 10.000) = 772 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     20.259 ms/op
     p(99.9900) =     25.835 ms/op
     p(99.9990) =     27.277 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 11.108 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.014 ms/op
Iteration   1: 4.217 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  21.932 ms/op
                 listUser·p0.9999: 26.774 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 4.118 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 4.037 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 18.517 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232617
  mean =      4.123 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 221392 
    [ 5.000,  7.500) = 8038 
    [ 7.500, 10.000) = 2137 
    [10.000, 12.500) = 398 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     27.537 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.124 ± 4.983  ops/ms
ClientPb.existUser                       thrpt       3   9.641 ± 4.602  ops/ms
ClientPb.getUser                         thrpt       3   9.271 ± 4.195  ops/ms
ClientPb.listUser                        thrpt       3   7.965 ± 5.017  ops/ms
ClientPb.createUser                       avgt       3   3.464 ± 2.216   ms/op
ClientPb.existUser                        avgt       3   3.319 ± 0.376   ms/op
ClientPb.getUser                          avgt       3   3.668 ± 2.460   ms/op
ClientPb.listUser                         avgt       3   4.135 ± 0.748   ms/op
ClientPb.createUser                     sample  264620   3.626 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.274           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.461           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.768           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.586           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.705           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.802           ms/op
ClientPb.existUser                      sample  291429   3.292 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.137           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.714           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.815           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.852           ms/op
ClientPb.getUser                        sample  275756   3.482 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.035           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.259           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.835           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  232617   4.123 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.917           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.760           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.838           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
