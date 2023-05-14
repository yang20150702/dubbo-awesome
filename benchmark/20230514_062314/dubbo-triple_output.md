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
# Warmup Iteration   1: 2.288 ops/ms
# Warmup Iteration   2: 5.366 ops/ms
# Warmup Iteration   3: 9.107 ops/ms
Iteration   1: 9.343 ops/ms
Iteration   2: 9.544 ops/ms
Iteration   3: 9.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.431 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (9.343, 9.431, 9.544), stdev = 0.103
  CI (99.9%): [7.555, 11.307] (assumes normal distribution)


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
# Warmup Iteration   1: 3.882 ops/ms
# Warmup Iteration   2: 9.081 ops/ms
# Warmup Iteration   3: 9.566 ops/ms
Iteration   1: 9.657 ops/ms
Iteration   2: 9.853 ops/ms
Iteration   3: 9.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.795 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (9.657, 9.795, 9.874), stdev = 0.120
  CI (99.9%): [7.612, 11.978] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.368 ops/ms
# Warmup Iteration   2: 8.771 ops/ms
# Warmup Iteration   3: 8.778 ops/ms
Iteration   1: 9.177 ops/ms
Iteration   2: 9.433 ops/ms
Iteration   3: 9.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.308 ±(99.9%) 2.341 ops/ms [Average]
  (min, avg, max) = (9.177, 9.308, 9.433), stdev = 0.128
  CI (99.9%): [6.967, 11.648] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.041 ops/ms
# Warmup Iteration   2: 7.403 ops/ms
# Warmup Iteration   3: 8.140 ops/ms
Iteration   1: 7.880 ops/ms
Iteration   2: 7.867 ops/ms
Iteration   3: 8.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.998 ±(99.9%) 3.919 ops/ms [Average]
  (min, avg, max) = (7.867, 7.998, 8.246), stdev = 0.215
  CI (99.9%): [4.078, 11.917] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.540 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.009 ms/op
Iteration   1: 3.397 ±(99.9%) 0.005 ms/op
Iteration   2: 3.382 ±(99.9%) 0.005 ms/op
Iteration   3: 3.459 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.412 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (3.382, 3.412, 3.459), stdev = 0.041
  CI (99.9%): [2.671, 4.154] (assumes normal distribution)


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
# Warmup Iteration   1: 8.797 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
Iteration   1: 3.305 ±(99.9%) 0.008 ms/op
Iteration   2: 3.192 ±(99.9%) 0.009 ms/op
Iteration   3: 3.300 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.266 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (3.192, 3.266, 3.305), stdev = 0.064
  CI (99.9%): [2.100, 4.432] (assumes normal distribution)


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
# Warmup Iteration   1: 8.708 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.002 ms/op
Iteration   1: 3.392 ±(99.9%) 0.003 ms/op
Iteration   2: 3.336 ±(99.9%) 0.010 ms/op
Iteration   3: 3.405 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.378 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (3.336, 3.378, 3.405), stdev = 0.037
  CI (99.9%): [2.706, 4.050] (assumes normal distribution)


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
# Warmup Iteration   1: 11.471 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.005 ms/op
Iteration   1: 4.026 ±(99.9%) 0.011 ms/op
Iteration   2: 3.811 ±(99.9%) 0.012 ms/op
Iteration   3: 3.955 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.931 ±(99.9%) 1.994 ms/op [Average]
  (min, avg, max) = (3.811, 3.931, 4.026), stdev = 0.109
  CI (99.9%): [1.937, 5.924] (assumes normal distribution)


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
# Warmup Iteration   1: 10.265 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
Iteration   1: 3.503 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  20.435 ms/op
                 createUser·p0.9999: 23.097 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  21.473 ms/op
                 createUser·p0.9999: 27.435 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   3: 3.353 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.262 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  20.767 ms/op
                 createUser·p0.9999: 25.935 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280454
  mean =      3.422 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11782 
    [ 2.500,  5.000) = 258654 
    [ 5.000,  7.500) = 8500 
    [ 7.500, 10.000) = 949 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     20.620 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     28.383 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 8.327 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
Iteration   1: 3.246 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  18.757 ms/op
                 existUser·p0.9999: 23.241 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 3.277 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  9.964 ms/op
                 existUser·p0.9999: 25.482 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 27.080 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294023
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16771 
    [ 2.500,  5.000) = 271307 
    [ 5.000,  7.500) = 4965 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     26.431 ms/op
     p(99.9990) =     27.784 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 9.679 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.011 ms/op
Iteration   1: 3.427 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  12.747 ms/op
                 getUser·p0.9999: 21.550 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 3.540 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  22.334 ms/op
                 getUser·p0.9999: 24.868 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  20.035 ms/op
                 getUser·p0.9999: 24.696 ms/op
                 getUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277286
  mean =      3.461 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5419 
    [ 2.500,  5.000) = 262077 
    [ 5.000,  7.500) = 8471 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     12.791 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     25.505 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 10.383 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.014 ms/op
Iteration   1: 3.997 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  17.890 ms/op
                 listUser·p0.9999: 37.224 ms/op
                 listUser·p1.00:   37.683 ms/op

Iteration   2: 4.062 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.817 ms/op
                 listUser·p0.9999: 18.924 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   3: 3.902 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 18.966 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240749
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 232275 
    [ 5.000,  7.500) = 6363 
    [ 7.500, 10.000) = 1275 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     36.630 ms/op
     p(99.9990) =     37.656 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.431 ± 1.876  ops/ms
ClientPb.existUser                       thrpt       3   9.795 ± 2.183  ops/ms
ClientPb.getUser                         thrpt       3   9.308 ± 2.341  ops/ms
ClientPb.listUser                        thrpt       3   7.998 ± 3.919  ops/ms
ClientPb.createUser                       avgt       3   3.412 ± 0.742   ms/op
ClientPb.existUser                        avgt       3   3.266 ± 1.166   ms/op
ClientPb.getUser                          avgt       3   3.378 ± 0.672   ms/op
ClientPb.listUser                         avgt       3   3.931 ± 1.994   ms/op
ClientPb.createUser                     sample  280454   3.422 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.110           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.620           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.575           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.443           ms/op
ClientPb.existUser                      sample  294023   3.264 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.841           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.089           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.431           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.508           ms/op
ClientPb.getUser                        sample  277286   3.461 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.368           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.791           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.543           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.870           ms/op
ClientPb.listUser                       sample  240749   3.986 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.575           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.958           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.630           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.683           ms/op
