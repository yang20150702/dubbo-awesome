# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.647 ops/ms
# Warmup Iteration   2: 3.557 ops/ms
# Warmup Iteration   3: 7.233 ops/ms
Iteration   1: 7.390 ops/ms
Iteration   2: 7.867 ops/ms
Iteration   3: 8.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.770 ±(99.9%) 6.246 ops/ms [Average]
  (min, avg, max) = (7.390, 7.770, 8.053), stdev = 0.342
  CI (99.9%): [1.524, 14.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.314 ops/ms
# Warmup Iteration   2: 6.847 ops/ms
# Warmup Iteration   3: 7.713 ops/ms
Iteration   1: 8.253 ops/ms
Iteration   2: 8.568 ops/ms
Iteration   3: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.411 ±(99.9%) 2.870 ops/ms [Average]
  (min, avg, max) = (8.253, 8.411, 8.568), stdev = 0.157
  CI (99.9%): [5.541, 11.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.061 ops/ms
# Warmup Iteration   2: 6.340 ops/ms
# Warmup Iteration   3: 7.709 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 8.395 ops/ms
Iteration   3: 8.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.172 ±(99.9%) 4.562 ops/ms [Average]
  (min, avg, max) = (7.902, 8.172, 8.395), stdev = 0.250
  CI (99.9%): [3.610, 12.734] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.255 ops/ms
# Warmup Iteration   2: 5.772 ops/ms
# Warmup Iteration   3: 6.628 ops/ms
Iteration   1: 6.694 ops/ms
Iteration   2: 6.934 ops/ms
Iteration   3: 7.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.911 ±(99.9%) 3.757 ops/ms [Average]
  (min, avg, max) = (6.694, 6.911, 7.104), stdev = 0.206
  CI (99.9%): [3.154, 10.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 16.324 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.420 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.008 ms/op
Iteration   1: 3.971 ±(99.9%) 0.006 ms/op
Iteration   2: 3.934 ±(99.9%) 0.011 ms/op
Iteration   3: 4.103 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.003 ±(99.9%) 1.618 ms/op [Average]
  (min, avg, max) = (3.934, 4.003, 4.103), stdev = 0.089
  CI (99.9%): [2.385, 5.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.397 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.004 ms/op
Iteration   1: 3.947 ±(99.9%) 0.005 ms/op
Iteration   2: 3.756 ±(99.9%) 0.008 ms/op
Iteration   3: 3.883 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.862 ±(99.9%) 1.772 ms/op [Average]
  (min, avg, max) = (3.756, 3.862, 3.947), stdev = 0.097
  CI (99.9%): [2.090, 5.635] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.437 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.014 ms/op
Iteration   1: 3.879 ±(99.9%) 0.005 ms/op
Iteration   2: 4.137 ±(99.9%) 0.006 ms/op
Iteration   3: 3.889 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.968 ±(99.9%) 2.663 ms/op [Average]
  (min, avg, max) = (3.879, 3.968, 4.137), stdev = 0.146
  CI (99.9%): [1.305, 6.631] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.561 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.827 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.878 ±(99.9%) 0.008 ms/op
Iteration   1: 4.854 ±(99.9%) 0.012 ms/op
Iteration   2: 4.473 ±(99.9%) 0.015 ms/op
Iteration   3: 4.611 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.646 ±(99.9%) 3.519 ms/op [Average]
  (min, avg, max) = (4.473, 4.646, 4.854), stdev = 0.193
  CI (99.9%): [1.127, 8.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.139 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.848 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.497 ±(99.9%) 0.018 ms/op
Iteration   1: 4.018 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.448 ms/op
                 createUser·p0.99:   7.979 ms/op
                 createUser·p0.999:  11.289 ms/op
                 createUser·p0.9999: 25.005 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 4.027 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  23.187 ms/op
                 createUser·p0.9999: 27.066 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 3.822 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  26.826 ms/op
                 createUser·p0.9999: 29.119 ms/op
                 createUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242640
  mean =      3.953 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 642 
    [ 2.500,  5.000) = 229125 
    [ 5.000,  7.500) = 10580 
    [ 7.500, 10.000) = 1757 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 95 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     22.196 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     29.403 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.004 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.902 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.014 ms/op
Iteration   1: 3.806 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.942 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  24.470 ms/op
                 existUser·p0.9999: 28.128 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 3.804 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  10.518 ms/op
                 existUser·p0.9999: 26.418 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.774 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  24.697 ms/op
                 existUser·p0.9999: 30.393 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252799
  mean =      3.795 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 351 
    [ 2.500,  5.000) = 245099 
    [ 5.000,  7.500) = 5871 
    [ 7.500, 10.000) = 957 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     23.652 ms/op
     p(99.9900) =     29.431 ms/op
     p(99.9990) =     30.729 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.082 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 4.697 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
Iteration   1: 4.110 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.590 ms/op
                 getUser·p0.999:  23.016 ms/op
                 getUser·p0.9999: 27.703 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 4.123 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  14.357 ms/op
                 getUser·p0.9999: 28.516 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   3: 3.996 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  27.689 ms/op
                 getUser·p0.9999: 32.276 ms/op
                 getUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235571
  mean =      4.076 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 125 
    [ 2.500,  5.000) = 218613 
    [ 5.000,  7.500) = 14139 
    [ 7.500, 10.000) = 1828 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     23.434 ms/op
     p(99.9900) =     30.587 ms/op
     p(99.9990) =     32.715 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.793 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.405 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.920 ±(99.9%) 0.019 ms/op
Iteration   1: 4.661 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  23.757 ms/op
                 listUser·p0.9999: 27.254 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   2: 4.906 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  21.001 ms/op
                 listUser·p0.9999: 23.555 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 4.774 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  17.173 ms/op
                 listUser·p0.9999: 19.638 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200586
  mean =      4.778 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 159991 
    [ 5.000,  7.500) = 35480 
    [ 7.500, 10.000) = 3705 
    [10.000, 12.500) = 832 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.642 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.250 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     21.477 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     27.950 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.770 ± 6.246  ops/ms
ClientPb.existUser                       thrpt       3   8.411 ± 2.870  ops/ms
ClientPb.getUser                         thrpt       3   8.172 ± 4.562  ops/ms
ClientPb.listUser                        thrpt       3   6.911 ± 3.757  ops/ms
ClientPb.createUser                       avgt       3   4.003 ± 1.618   ms/op
ClientPb.existUser                        avgt       3   3.862 ± 1.772   ms/op
ClientPb.getUser                          avgt       3   3.968 ± 2.663   ms/op
ClientPb.listUser                         avgt       3   4.646 ± 3.519   ms/op
ClientPb.createUser                     sample  242640   3.953 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.452           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.196           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.541           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.917           ms/op
ClientPb.existUser                      sample  252799   3.795 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.284           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.141           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.611           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.652           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.431           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  235571   4.076 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.750           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.784           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.782           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.434           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.587           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.063           ms/op
ClientPb.listUser                       sample  200586   4.778 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.642           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.250           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.257           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.477           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.756           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.000           ms/op
