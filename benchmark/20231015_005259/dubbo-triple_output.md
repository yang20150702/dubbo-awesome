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
# Warmup Iteration   1: 2.160 ops/ms
# Warmup Iteration   2: 5.075 ops/ms
# Warmup Iteration   3: 8.447 ops/ms
Iteration   1: 8.963 ops/ms
Iteration   2: 9.095 ops/ms
Iteration   3: 9.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.101 ±(99.9%) 2.571 ops/ms [Average]
  (min, avg, max) = (8.963, 9.101, 9.245), stdev = 0.141
  CI (99.9%): [6.530, 11.672] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 8.928 ops/ms
# Warmup Iteration   3: 9.398 ops/ms
Iteration   1: 9.430 ops/ms
Iteration   2: 9.647 ops/ms
Iteration   3: 9.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.539 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (9.430, 9.539, 9.647), stdev = 0.109
  CI (99.9%): [7.560, 11.519] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.789 ops/ms
# Warmup Iteration   2: 8.253 ops/ms
# Warmup Iteration   3: 9.024 ops/ms
Iteration   1: 8.885 ops/ms
Iteration   2: 9.375 ops/ms
Iteration   3: 9.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.160 ±(99.9%) 4.569 ops/ms [Average]
  (min, avg, max) = (8.885, 9.160, 9.375), stdev = 0.250
  CI (99.9%): [4.591, 13.729] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.768 ops/ms
# Warmup Iteration   2: 7.099 ops/ms
# Warmup Iteration   3: 7.588 ops/ms
Iteration   1: 7.546 ops/ms
Iteration   2: 7.536 ops/ms
Iteration   3: 7.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.575 ±(99.9%) 1.063 ops/ms [Average]
  (min, avg, max) = (7.536, 7.575, 7.642), stdev = 0.058
  CI (99.9%): [6.512, 8.637] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.008 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.004 ms/op
Iteration   1: 3.501 ±(99.9%) 0.006 ms/op
Iteration   2: 3.494 ±(99.9%) 0.004 ms/op
Iteration   3: 3.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.504 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.494, 3.504, 3.516), stdev = 0.011
  CI (99.9%): [3.305, 3.702] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.442 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.004 ms/op
Iteration   1: 3.414 ±(99.9%) 0.004 ms/op
Iteration   2: 3.401 ±(99.9%) 0.003 ms/op
Iteration   3: 3.378 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.397 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (3.378, 3.397, 3.414), stdev = 0.018
  CI (99.9%): [3.066, 3.729] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.201 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.003 ms/op
Iteration   1: 3.445 ±(99.9%) 0.004 ms/op
Iteration   2: 3.414 ±(99.9%) 0.007 ms/op
Iteration   3: 3.490 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.450 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (3.414, 3.450, 3.490), stdev = 0.038
  CI (99.9%): [2.757, 4.142] (assumes normal distribution)


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
# Warmup Iteration   1: 9.855 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.007 ms/op
Iteration   1: 4.106 ±(99.9%) 0.009 ms/op
Iteration   2: 4.184 ±(99.9%) 0.007 ms/op
Iteration   3: 4.031 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.107 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (4.031, 4.107, 4.184), stdev = 0.076
  CI (99.9%): [2.712, 5.502] (assumes normal distribution)


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
# Warmup Iteration   1: 10.541 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.015 ms/op
Iteration   1: 3.544 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  21.617 ms/op
                 createUser·p0.9999: 35.127 ms/op
                 createUser·p1.00:   36.831 ms/op

Iteration   2: 3.554 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  12.861 ms/op
                 createUser·p0.9999: 27.394 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.359 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  23.989 ms/op
                 createUser·p0.9999: 30.176 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271234
  mean =      3.539 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5290 
    [ 2.500,  5.000) = 257275 
    [ 5.000,  7.500) = 7270 
    [ 7.500, 10.000) = 778 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     21.390 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     35.644 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 8.198 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.010 ms/op
Iteration   1: 3.407 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  22.512 ms/op
                 existUser·p0.9999: 25.186 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 3.380 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  22.349 ms/op
                 existUser·p0.9999: 27.611 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   3: 3.415 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  13.926 ms/op
                 existUser·p0.9999: 27.972 ms/op
                 existUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282242
  mean =      3.401 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13379 
    [ 2.500,  5.000) = 260515 
    [ 5.000,  7.500) = 6908 
    [ 7.500, 10.000) = 702 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     21.029 ms/op
     p(99.9900) =     27.288 ms/op
     p(99.9990) =     28.537 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 8.624 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.013 ms/op
Iteration   1: 3.441 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  16.944 ms/op
                 getUser·p0.9999: 23.246 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   2: 3.466 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  15.544 ms/op
                 getUser·p0.9999: 23.684 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   3: 3.548 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  23.626 ms/op
                 getUser·p0.9999: 28.638 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275333
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3752 
    [ 2.500,  5.000) = 262215 
    [ 5.000,  7.500) = 7678 
    [ 7.500, 10.000) = 1055 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     16.051 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     29.482 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.365 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.015 ms/op
Iteration   1: 4.224 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.654 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.757 ms/op
                 listUser·p0.999:  19.428 ms/op
                 listUser·p0.9999: 24.651 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 4.200 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 26.417 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   3: 4.274 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.145 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  15.910 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226752
  mean =      4.232 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 128 
    [ 2.500,  5.000) = 214132 
    [ 5.000,  7.500) = 9179 
    [ 7.500, 10.000) = 2367 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     24.389 ms/op
     p(99.9990) =     27.180 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.101 ± 2.571  ops/ms
ClientPb.existUser                       thrpt       3   9.539 ± 1.979  ops/ms
ClientPb.getUser                         thrpt       3   9.160 ± 4.569  ops/ms
ClientPb.listUser                        thrpt       3   7.575 ± 1.063  ops/ms
ClientPb.createUser                       avgt       3   3.504 ± 0.199   ms/op
ClientPb.existUser                        avgt       3   3.397 ± 0.331   ms/op
ClientPb.getUser                          avgt       3   3.450 ± 0.693   ms/op
ClientPb.listUser                         avgt       3   4.107 ± 1.395   ms/op
ClientPb.createUser                     sample  271234   3.539 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.359           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.390           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.474           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.831           ms/op
ClientPb.existUser                      sample  282242   3.401 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.853           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.791           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.029           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.288           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.327           ms/op
ClientPb.getUser                        sample  275333   3.484 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.133           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.004           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.051           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.280           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  226752   4.232 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.654           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.055           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.296           ms/op
