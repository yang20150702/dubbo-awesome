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
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 5.281 ops/ms
# Warmup Iteration   3: 8.747 ops/ms
Iteration   1: 9.127 ops/ms
Iteration   2: 9.095 ops/ms
Iteration   3: 9.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.187 ±(99.9%) 2.418 ops/ms [Average]
  (min, avg, max) = (9.095, 9.187, 9.339), stdev = 0.133
  CI (99.9%): [6.769, 11.605] (assumes normal distribution)


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
# Warmup Iteration   1: 2.820 ops/ms
# Warmup Iteration   2: 8.553 ops/ms
# Warmup Iteration   3: 9.706 ops/ms
Iteration   1: 9.552 ops/ms
Iteration   2: 9.702 ops/ms
Iteration   3: 9.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.596 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (9.535, 9.596, 9.702), stdev = 0.092
  CI (99.9%): [7.922, 11.270] (assumes normal distribution)


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
# Warmup Iteration   1: 2.924 ops/ms
# Warmup Iteration   2: 8.424 ops/ms
# Warmup Iteration   3: 8.945 ops/ms
Iteration   1: 9.508 ops/ms
Iteration   2: 9.499 ops/ms
Iteration   3: 9.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.460 ±(99.9%) 1.370 ops/ms [Average]
  (min, avg, max) = (9.373, 9.460, 9.508), stdev = 0.075
  CI (99.9%): [8.090, 10.831] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.830 ops/ms
# Warmup Iteration   2: 6.806 ops/ms
# Warmup Iteration   3: 7.733 ops/ms
Iteration   1: 7.636 ops/ms
Iteration   2: 7.811 ops/ms
Iteration   3: 8.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.843 ±(99.9%) 4.120 ops/ms [Average]
  (min, avg, max) = (7.636, 7.843, 8.084), stdev = 0.226
  CI (99.9%): [3.724, 11.963] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.788 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.006 ms/op
Iteration   1: 3.563 ±(99.9%) 0.004 ms/op
Iteration   2: 3.657 ±(99.9%) 0.005 ms/op
Iteration   3: 3.496 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.572 ±(99.9%) 1.479 ms/op [Average]
  (min, avg, max) = (3.496, 3.572, 3.657), stdev = 0.081
  CI (99.9%): [2.093, 5.051] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.208 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.003 ms/op
Iteration   1: 3.367 ±(99.9%) 0.004 ms/op
Iteration   2: 3.343 ±(99.9%) 0.003 ms/op
Iteration   3: 3.287 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.332 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.287, 3.332, 3.367), stdev = 0.041
  CI (99.9%): [2.588, 4.077] (assumes normal distribution)


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
# Warmup Iteration   1: 7.780 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.003 ms/op
Iteration   1: 3.491 ±(99.9%) 0.003 ms/op
Iteration   2: 3.442 ±(99.9%) 0.005 ms/op
Iteration   3: 3.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.451 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.419, 3.451, 3.491), stdev = 0.037
  CI (99.9%): [2.776, 4.125] (assumes normal distribution)


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
# Warmup Iteration   1: 10.468 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.005 ms/op
Iteration   1: 4.205 ±(99.9%) 0.005 ms/op
Iteration   2: 4.001 ±(99.9%) 0.013 ms/op
Iteration   3: 4.099 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.102 ±(99.9%) 1.859 ms/op [Average]
  (min, avg, max) = (4.001, 4.102, 4.205), stdev = 0.102
  CI (99.9%): [2.243, 5.961] (assumes normal distribution)


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
# Warmup Iteration   1: 9.982 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
Iteration   1: 3.385 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  20.956 ms/op
                 createUser·p0.9999: 23.207 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   2: 3.602 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  22.008 ms/op
                 createUser·p0.9999: 25.862 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.532 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.552 ms/op
                 createUser·p0.999:  16.402 ms/op
                 createUser·p0.9999: 25.884 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273987
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13262 
    [ 2.500,  5.000) = 252648 
    [ 5.000,  7.500) = 6408 
    [ 7.500, 10.000) = 1095 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     25.710 ms/op
     p(99.9990) =     26.502 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.275 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
Iteration   1: 3.487 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.336 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 27.749 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.249 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  21.324 ms/op
                 existUser·p0.9999: 24.411 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   3: 3.347 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  21.856 ms/op
                 existUser·p0.9999: 27.329 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282380
  mean =      3.399 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9214 
    [ 2.500,  5.000) = 265937 
    [ 5.000,  7.500) = 5839 
    [ 7.500, 10.000) = 978 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 142 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     11.892 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     28.379 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 9.984 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.013 ms/op
Iteration   1: 3.523 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  20.327 ms/op
                 getUser·p0.9999: 23.623 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 28.076 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.514 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  25.002 ms/op
                 getUser·p0.9999: 28.108 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273711
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11411 
    [ 2.500,  5.000) = 252029 
    [ 5.000,  7.500) = 8665 
    [ 7.500, 10.000) = 1133 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 113 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     27.754 ms/op
     p(99.9990) =     28.418 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 11.915 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.407 ±(99.9%) 0.015 ms/op
Iteration   1: 4.262 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   8.592 ms/op
                 listUser·p0.999:  20.114 ms/op
                 listUser·p0.9999: 24.673 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 4.036 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 16.976 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 4.271 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  15.256 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229233
  mean =      4.187 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 217456 
    [ 5.000,  7.500) = 8759 
    [ 7.500, 10.000) = 1975 
    [10.000, 12.500) = 497 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     15.823 ms/op
     p(99.9900) =     23.530 ms/op
     p(99.9990) =     25.334 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.187 ± 2.418  ops/ms
ClientPb.existUser                       thrpt       3   9.596 ± 1.674  ops/ms
ClientPb.getUser                         thrpt       3   9.460 ± 1.370  ops/ms
ClientPb.listUser                        thrpt       3   7.843 ± 4.120  ops/ms
ClientPb.createUser                       avgt       3   3.572 ± 1.479   ms/op
ClientPb.existUser                        avgt       3   3.332 ± 0.745   ms/op
ClientPb.getUser                          avgt       3   3.451 ± 0.674   ms/op
ClientPb.listUser                         avgt       3   4.102 ± 1.859   ms/op
ClientPb.createUser                     sample  273987   3.504 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.079           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.285           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.710           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  282380   3.399 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.249           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.242           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.892           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.197           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  273711   3.508 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.993           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.754           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  229233   4.187 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.268           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.192           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.823           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.530           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.461           ms/op
